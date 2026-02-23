# PYTHON-LAB-IEEE
| Name | Role | Email |
|-----|-----|------|
| John Doe | Project Manager | john@gmail.com |
| Jane Smith | Project Owner | jane@gmail.com |
| Alex Brown | Developer | alex@gmail.com |
| Maria Lee | Administrator | maria@gmail.com |


```bash
ant package.src \
-Diics.release=./conf/iics.release.properties \
-Diics.target.environment=prod \
-Diics.target.package.config=./conf/all_designs.package.txt \
-Diics.package.transform.config=../../../conf/prod.transform.properties \
-Dtools.transform.disabled=false

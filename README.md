# CI

[![CI][ci-badge]][ci-badge-url]

[ci-badge]: https://github.com/Khalshim/testuml/actions/workflows/blank.yml/badge.svg
[ci-badge-url]: https://github.com/Khalshim/testuml/actions/workflows/blank.yml

# Shield :



![License](https://img.shields.io/github/license/Khalshim/testuml?style=plastic)

![Release](https://img.shields.io/github/v/release/Khalshim/testuml?style=plastic) 

![Tag](https://img.shields.io/github/v/tag/Khalshim/testuml?style=plastic)

![Filenumber](https://img.shields.io/github/directory-file-count/Khalshim/testuml?style=plastic)

![Linenumber](https://img.shields.io/tokei/lines/github/Khalshim/testuml?style=plastic)

# UML TEST :

![with Andrea's tip](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/Khalshim/testuml/main/docs/diagrams/mytest_uml.uml)



## Miscellaneous <a name="miscellaneous"></a>
### Sonarqube
#### Installing sonarqube server locally
* Connect to a VM
* Install docker and docker-compose
* Copy <code>sonarqube-docker-compose.yml</code> file
* type <code>docker-compose -f sonarqube-docker-compose.yml up</code>
* Connect to <code>\<VM_IP\>:9000</code> and follow instructions
#### To generate sonarqube report :
* Checkout <code>main</code> branch
Don't scan another branch than main as the community version doesn't handle multiple branch scan.
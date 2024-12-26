# CAMSD Dataset: Cloud-Native Architecture Mining and Smell Detection

This repository contains the dataset used in the research paper, "CAMSD: Feature Engineering-Based Cloud-Native Architecture Mining and Smell Detection." The dataset consists of source code and associated architectural smell labels for ten open-source, Java-based cloud-native applications.

## Dataset Overview

The dataset includes ten cloud-native applications of varying sizes and domains, all with accompanying cloud-native deployment configurations.  A detailed breakdown of these applications is provided in Table 1 below.

Architectural smells within each application component were manually labeled by the authors, guided by well-defined smell definitions.

**Important Note:** Five of the applications (marked with an asterisk (*) in Table 1) have been refactored using Spring Cloud and Kubernetes specifications as part of this research. This may introduce differences from the original versions of the projects.

**Table 1: Cloud-Native Applications**

| Project Name                      | Repository Link                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------------|
| PiggyMetrics*                    | https://github.com/sqshq/piggymetrics                                            |
| Spring-Microservices             | https://github.com/pranav-patil/spring-microservices                              |
| Spring-Petclinic-Msa             | https://github.com/spring2go/spring-petclinic-msa                                 |
| BookstoreApp*                    | https://github.com/devdcores/BookStoreApp-Distributed-Application                 |
| Micronaut-Microservices-Poc*     | https://github.com/asc-lab/micronaut-microservices-poc                           |
| Springboot-Microservices-Example | https://github.com/cevheri/springboot-microservices-example/tree/main           |
| Microservice K8S Sample          | https://github.com/alexwang66/sample-microservices-k8s                            |
| Train-Ticket                     | https://github.com/FudanSELab/train-ticket                                       |
| Ftgo-Application*                 | https://github.com/microservices-patterns/ftgo-application                     |
| Sample-Spring-Microservices*    | https://github.com/piomin/sample-spring-microservices                             |


# SysOps Assignment
Please implement deployment of 3 tier application via Ansible, Docker, Bash or Python scripting, which would run on Ubuntu server LTS, would use Postgres. You would need to automate deployment of:
1. Install PostgreSQL DBMS and create DB, user for DB, set users password.
2. Make sure all your changes are persistent after reboot.

## Preface
No prior docker experience to speak of, herewith my first *attempt* at creating a dockerfile and eventually (hopefully) a 3 tier architecture docker container. This noticeably shy on the  tangibles, but I hope to at least show my initiative.


### 3 Tier Architecture
1. Presentation Tier - REACT.js ?
2. Application Tier 
3. Data Tier - PostgreSQL


### Assumptions and Interpretations
That I will be ready for Ansible, Docker, Container orchestration with Kubernetes challenge when the time comes, even in the doing I have learn so much, there is a silver lining.

### TODO 
- Persistence
- Presentation Layer, could be REACT.js
- Add configure.sh to /docker-entrypoint-initdb.d

By Michael Forssman

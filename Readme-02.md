# CodoACodo
Trabajos realizados en el Codo A Codo, para el curso de Desarrollo FullStack Python

# Temas
- [AWS](#aws)
  - [Questions](#questions)
    - [EC2](#ec2-1)
      - [AMI](#ami)

****

<!-- ALL-TOPICS-LIST:START -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<center>
<table>
  <tr>
    <td align="center"><a href="topics/devops"><img src="images/devops.png" width="75px;" height="75px;" alt="DevOps" /><br /><b>DevOps</b></a></td>
    <td align="center"><a href="topics/cicd"><img src="images/cicd.png" width="75px;" height="75px;" alt="cicd"/><br /><b>CI/CD</b></a></td>
    <td align="center"><a href="topics/git"><img src="images/git.png" width="75px;" height="75px;" alt="Git"/><br /><b>Git</b></a></td>
    <td align="center"><a href="topics/ansible"><img src="images/ansible.png" width="75px;" height="75px;" alt="ansible"/><br /><b>Ansible</b></a></td>
    <td align="center"><a href="#network"><img src="images/network.png" width="75px;" height="75px;" alt="Network"/><br /><b>Network</b></a></td>
  </tr>
</table>
</center>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-TOPICS-LIST:END -->

****

## Operating System

### Operating System Exercises

|Name|Topic|Objective & Instructions|Solution|Comments|
|--------|--------|------|----|----|
| Fork 101 | Fork | [Exercise](topics/os/fork_101.md) | [Link](topics/os/solutions/fork_101_solution.md) | |
| Fork 102 | Fork | [Exercise](topics/os/fork_102.md) | [Link](topics/os/solutions/fork_102_solution.md) | |

****

# Ejercicios realizados

##HTML

|Name|Topic|Objective & Instructions|Solution|Comments|
|--------|--------|------|----|----|
| Create a User | IAM | [Exercise](exercises/create_user/exercise.md) | [Solution](exercises/create_user/solution.md) | |
| Password Policy | IAM | [Exercise](exercises/password_policy_and_mfa/exercise.md) | [Solution](exercises/password_policy_and_mfa/solution.md) | |

## Questions

### Global Infrastructure

<details>
<summary>Explain the following

  * Availability zone
  * Region
  * Edge location</summary><br><b>

AWS regions are data centers hosted across different geographical locations worldwide.<br>

Within each region, there are multiple isolated locations known as Availability Zones. Each availability zone is one or more data-centers with redundant network and connectivity and power supply. Multiple availability zones ensure high availability in case one of them goes down.<br>

Edge locations are basically content delivery network which caches data and insures lower latency and faster delivery to the users in any location. They are located in major cities in the world.
</b></details>

### EC2

<details>
<summary>What is EC2?</summary><br><b>

"a web service that provides secure, resizable compute capacity in the cloud".
Read more [here](https://aws.amazon.com/ec2)
</b></details>

<details>
<summary>True or False? EC2 is a regional service</summary><br><b>

True. As opposed to IAM for example, which is a global service, EC2 is a regional service.
</b></details>

<details>
<summary>What are some of the properties/configuration options of EC2 instances that can be set or modified?</summary><br><b>

* OS (Linux, Windows)
* RAM and CPU
* Networking - IP, Card properties like speed
* Storage Space - (EBS, EFS, EC2 Instance Store)
* EC2 User Data
* Security groups
</b></details>






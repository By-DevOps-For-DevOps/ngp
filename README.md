# NGP

<img src="https://github.com/microservices-today/microservices-today.github.io/blob/master/source/images/logo.png?raw=true" width="100">

---

Our mission is to provide a simple but robust mechanisms for deployment, maintenance, and scaling of your microservices in any cloud service provider by utilizing best practices.

One of the major trends in cloud service platform over the past few years has been increased automation and a concurrent decrease in the need for human or manual intervention. Many Engineering teams still rely on manual configurations, custom scripts, golden images or outdated tools to manage infrastructure, resulting in errors and slow deployments. Organizations looking for faster deployments treat infrastructure like software: as code that can be managed with the same tools and processes software developers use, such as version control, continuous integration, code review and automated testing.

Using NGP to describe your infrastructure lets you make infrastructure changes more easily, rapidly, safely and reliably.
NGP based on IaC (Infrastructure as Code) that helps you model and setup a complete infrastructure and related services to run your microservices.

Moreover, NGP is fully open source and transparent.

---

## Roadmap

<table>
    <thead>
        <tr>
            <th rowspan=2>Cloud</th>
            <th rowspan=2>Orchestration</th>
            <th rowspan=2>IaC</th>
            <th rowspan=2>CICD</th>
            <th colspan=3>Task</th>
        </tr>
        <tr>    
            <th>API/Web</th>
            <th>Queue</th>
            <th>Job</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4>AWS</td>
            <td rowspan=2>ECS</td>
            <td><a href="https://github.com/microservices-today/ecs-iac/releases/tag/3.0.2">ecs-iac v3.0.2</a>(EC2)</td>
            <td><a href="https://github.com/microservices-today/ecs-cicd/releases/tag/2.1.0">ecs-cicd v2.1.0</a></td>
            <td><a href="https://github.com/microservices-today/ecs-api/tree/1.0.1">ecs-api v1.0.1</a></td>
            <td><a href="https://github.com/microservices-today/ecs-mq/releases/tag/1.0.0">ecs-mq v1.0.0</a></td>
            <td><a href="https://github.com/microservices-today/ecs-job/releases/tag/1.0.0">ecs-job v1.0.0</a></td>
        </tr>
        <tr>
            <td><a href="https://github.com/microservices-today/ecs-iac/releases/tag/3.0.5">ecs-iac v3.0.5</a>(Fargate)</td>
            <td><a href="https://github.com/microservices-today/ecs-cicd/releases/tag/3.0.2">ecs-cicd v3.0.2</a></td>
            <td><a href="https://github.com/microservices-today/ecs-api/releases/tag/2.1.1">ecs-api v2.1.1</a></td>
            <td><a href="https://github.com/microservices-today/ecs-mq/releases/tag/2.0.2">ecs-mq v2.0.2</a></td>
            <td><a href="https://github.com/microservices-today/ecs-job/releases/tag/2.0.1">ecs-job v2.0.1</a></td>
        </tr>
        <tr>
            <td rowspan=2>EKS</td>
            <td>TBD</td>
            <td>TBD</td>
            <td>TBD</td>
            <td>TBD</td>
            <td>TBD</td>
        </tr>
    </tbody>
    <tbody>
        <tr>
            <td rowspan=4>GCP</td>
            <td rowspan=2>GKE</td>
            <td><a href="https://github.com/By-DevOps-For-DevOps/gke-iac/releases/tag/1.0.0">gke-iac v1.0.0</a>(GKE)</td>
            <td>TBD</td>
            <td>TBD</td>
            <td>TBD</td>
            <td>TBD</td>
        </tr>
    </tbody>
        <tbody>
        <tr>
            <td rowspan=4>Azure</td>
            <td rowspan=2>AKS</td>
            <td>TBD</td>
            <td>TBD</td>
            <td>TBD</td>
            <td>TBD</td>
            <td>TBD</td>
        </tr>
    </tbody>
</table>

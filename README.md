|NAME|PROMPT|DESCRIPTION|EXAMPLE|
|-|-|-|-|
|app.yaml|create pod with image gcr.io/k8s-glc/w5-task2:v2.0.0 port 8080|Create Pod with gcr.io/k8s-glc/w5-task2:v2.0.0 image|https://raw.githubusercontent.com/fry88/w5_t3/main/app.yaml|
|app-resources.yaml|create pod app-resource liveness/, readiness/ready, res req cpu:100 mem:128 lim cpu:100 mem 256,image gcr.io/k8s-glc/w5-task2:v2.0.0 port 8080|Create Pod with resources|https://raw.githubusercontent.com/fry88/w5_t3/main/app-resources.yaml|
|app-readinessProbe.yaml|create Pod with liveness/,readiness/ready image nickp6/bbrc:v1.0.0 port 8080|Create Pod with nickp6/bbrc:v1.0.0 image and liveness-, readiness- probes|https://raw.githubusercontent.com/NickP007/les05/main/yaml/app-readinessProbe.yaml|

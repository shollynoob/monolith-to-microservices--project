# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)
* Travis CI showing a successful build and deploy job

## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
![kubectl get pods](https://user-images.githubusercontent.com/5302985/192177289-28f3440b-2144-42df-945f-d5c7c2950eca.PNG)

* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
![kubectl_describe_services_A](https://user-images.githubusercontent.com/5302985/192177518-42c2a8e3-ee7d-445b-9b21-bf02cde0cc7c.PNG)
![kubectl_describe_services_B](https://user-images.githubusercontent.com/5302985/192177557-d105a8d0-7f07-444e-8d96-c24f46f2ca2f.PNG)
![kubectl_describe_services_C](https://user-images.githubusercontent.com/5302985/192177572-ad44abf8-5b6d-4b56-9123-5300683638bc.PNG)
![kubectl_describe_services_D](https://user-images.githubusercontent.com/5302985/192177587-27981419-d233-4814-997f-aa1bd80a6b29.PNG)


* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
![Metric 1](https://user-images.githubusercontent.com/5302985/192178028-3c152f3d-9ddb-4fc5-b9c5-5dea1c4b5ce3.PNG)
![Metric 2](https://user-images.githubusercontent.com/5302985/192178049-e1e477e6-fdad-4770-8655-2217a3d8480c.PNG)
![Metric 3](https://user-images.githubusercontent.com/5302985/192178064-e91e2256-4bf3-4da5-9944-a6cdecdad5d5.PNG)
![Metric 4](https://user-images.githubusercontent.com/5302985/192178079-e55dd224-cc7f-4d94-943d-4b8685b93b68.PNG)

* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
![kubectl logs](https://user-images.githubusercontent.com/5302985/192177684-60a744fa-e4a5-48e3-a5ca-60f4ffd65f4f.PNG)


* DOcker hub
![Docker hub 1](https://user-images.githubusercontent.com/5302985/192178128-738ef37d-6018-41cb-bd57-8334808ad84c.PNG)
![Docker hub 2](https://user-images.githubusercontent.com/5302985/192178233-4c395790-b4c2-4a2e-bea9-12c483322017.PNG)
![Docker hub 3](https://user-images.githubusercontent.com/5302985/192178253-be309122-15f4-4ba0-b924-c198549ba5a7.PNG)
![docker hub 4](https://user-images.githubusercontent.com/5302985/192178273-f4d4a162-d229-48f3-80e8-58fea6653131.PNG)
![Docker hub 5](https://user-images.githubusercontent.com/5302985/192178285-1840a46d-60c1-4364-87ef-8635f2e7c73f.PNG)


* CircleCI
![CircleCi](https://user-images.githubusercontent.com/5302985/192178334-1f275a7e-ce43-4678-b23a-882dad245f79.PNG)
![Capture_final deployment](https://user-images.githubusercontent.com/5302985/192178353-3eab2525-9380-4d78-b412-02a17ad91b96.PNG)
![circleci_yaml file](https://user-images.githubusercontent.com/5302985/192178508-2a7636ed-362a-407f-8f34-3b169fdd4acb.PNG)



* Kubectl svc
![kubectl scv](https://user-images.githubusercontent.com/5302985/192178393-c83cc1ce-ff24-4c08-8473-af94c4625c7d.PNG)

* Deployment yaml
![deployment yaml1](https://user-images.githubusercontent.com/5302985/192178466-2999f9cc-da1d-419f-a761-80e6b9f53ad2.PNG)
![deployment yaml2](https://user-images.githubusercontent.com/5302985/192178488-b61c719a-cbbf-4cda-b392-27cedd6dfd27.PNG)

* Reverseproxy
![reverse-proxy](https://user-images.githubusercontent.com/5302985/192178541-62ea7851-c621-4bc5-a069-4c40a358fa6d.PNG)








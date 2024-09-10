# k8s-lab2
1. the created replicaSet : ![alt text](image.png)

2. the number of pods in the replicaSet :
    ![alt text](image-1.png)

3. the image used to create the replicaSet is busybox777 :
    ![alt text](image-2.png)

4. the number of ready images is 0 :
    ![alt text](image-3.png)

5. the pods is not ready because the images does not exist :
    ![alt text](image-4.png)

6. the number of available pods is 4  :
    ![alt text](image-5.png)

7. the number of available pods is also 4 because the down one is created again by the controller 

8. the file does not created :
 ![alt text](image-6.png)
 after adding : apiVersion: apps/v1 the file created 
 ![alt text](image-7.png)

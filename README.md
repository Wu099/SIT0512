#### usage
prepare mongodb-configmap
```groovy
kubectl apply -f mongdb-conifgmap.yaml
```
install mongodb
```groovy
kubectl apply -f mongodb-deploy.yaml
```

expose mongodb from service
```groovy
kubectl apply -f mongdb-svc.yaml
```

pic
![image.png](https://cdn.nlark.com/yuque/0/2024/png/36189502/1715492855579-50e51db9-71e4-4ad8-87f9-604fa31da2ba.png#averageHue=%23252525&clientId=ub6028c8c-1fb4-4&from=paste&height=284&id=u2884f459&originHeight=568&originWidth=1268&originalType=binary&ratio=2&rotation=0&showTitle=false&size=547360&status=done&style=none&taskId=ub5ed82f5-77cb-4476-bf5e-883f08d6131&title=&width=634)


![1281715492320_.pic.jpg](https://cdn.nlark.com/yuque/0/2024/jpeg/36189502/1715492862742-3604c057-2d00-4b99-9ccb-f02bf2190cc3.jpeg#averageHue=%23212121&clientId=ub6028c8c-1fb4-4&from=drop&id=u8a462658&originHeight=540&originWidth=1282&originalType=binary&ratio=2&rotation=0&showTitle=false&size=457055&status=done&style=none&taskId=ued9adc94-5d6e-426c-b543-abb3f047d93&title=)


![image.png](https://cdn.nlark.com/yuque/0/2024/png/36189502/1715613244373-df0c610a-ffe6-4aae-b69f-b417c5a6865f.png#averageHue=%23090909&clientId=u2c5aecc8-9849-4&from=paste&height=88&id=u658cbfda&originHeight=176&originWidth=790&originalType=binary&ratio=2&rotation=0&showTitle=false&size=39160&status=done&style=none&taskId=u5f071347-0a33-4aad-be82-0b9ddd83859&title=&width=395)

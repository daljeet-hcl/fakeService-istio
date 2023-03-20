# fakeService-istio
a sample project to test istio using service Mesh Testing tool from https://github.com/nicholasjackson/fake-service

some simple steps to TEST ISTIO and its functinality.

install istio and sample Bookinfo app as this app is dependent on bookinfo-gateway deployed by that sample app.

 curl 192.168.29.137/sample1-service  -H end-user:daljeet # this also sends traffic to v2subset of order service
 
 curl 192.168.29.137/sample1-service/api/v2/order  #sends traffic to v2 subset of order service

curl 192.168.29.137/sample1-service  -H end-user:daljeet12  # this also sends traffic to v2subset of order service

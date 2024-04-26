# Spring Boot "Hello World" Projesi
Bu proje, basit bir Spring Boot uygulamasıdır. "/hello" endpoint'ine gelen isteklere "Hello, World!" yanıtı verir.

## Neden Bu Proje?
Bu proje, Spring Boot'un temellerini anlamak ve bir Spring Boot uygulamasını Kubernetes üzerinde dağıtmak için bir örnek oluşturur. Ayrıca, Jenkins ve Docker gibi araçları kullanarak CI/CD sürecini anlamak için de bir örnek teşkil eder.

## Proje İçeriği
- src/main/java: Spring Boot uygulamasının Java kaynak kodunu içerir.
- Dockerfile: Spring Boot uygulamasını Docker konteynerine paketlemek için kullanılır.
- deployment.yaml: Kubernetes'te uygulamanın nasıl dağıtılacağını tanımlar.
- service.yaml: Kubernetes'te uygulamanın servisini oluşturur.
- ingress.yaml: Kubernetes'te uygulamaya erişimi sağlayan ingress kurallarını tanımlar.
- Jenkinsfile: Jenkins pipeline'ını tanımlar ve CI/CD sürecini otomatize eder.

## Nasıl Kullanılır?

1- Proje dosyalarını bilgisayarınıza klonlayın.
2- Spring Boot uygulamasını geliştirin veya değiştirin.
3- Docker konteynerine uygulamayı paketlemek için docker build komutunu kullanın.
4- Kubernetes cluster'ına uygulamayı dağıtmak için kubectl apply komutunu kullanarak YAML dosyalarını uygulayın.
5- Jenkins pipeline'ını yapılandırın ve GitHub deposundaki her değişiklik için otomatik CI/CD sürecini çalıştırın.

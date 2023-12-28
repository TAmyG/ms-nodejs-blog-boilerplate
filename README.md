
- docker build -t tamyvivas/ms-posts:0.0.2 .
- kubectl apply -f posts.yml
- kubectl rollout restart deployment [posts-depl] -> to update the pods pulling the images again
- kubectl apply -f posts-service.yml

- https://kubernetes.github.io/ingress-nginx/deploy/#quick-start
# Artemis


## When you build docker image and pushed, it will create new version for Artemis, after deploy you can see 10 versions in your GCP Account under Aartifact Registry
```
docker image build -t "Artemis Folder Name"/aretmis/artemis:1.0.0 .
```
```
docker push "Artemis Folder Name"/artemis:1.0.0
```
```
git checkout 1.0.0
```

<img width="689" alt="Screenshot 2023-04-01 at 3 17 22 PM" src="https://user-images.githubusercontent.com/103330632/229312876-5aec17e7-f5c0-40bd-88c7-cfac137d64eb.png">

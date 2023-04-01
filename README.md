# JobBox

JobBox is am application where you can find different developer jobs. You can search for the job. you can find popular jobs. Even nearby jobs. JobBox is created use react-native expo. and the backend data of jobs are been populated from JSearch API. You can find JSearch API in RapidAPI. 
#
![JobBox Screen](https://user-images.githubusercontent.com/81036521/229280459-445ad311-be3b-4d33-8fa8-6032018a9a82.png)

#

To access the app you will need to install [Expo Go](https://expo.dev/client) on you android or ios and scan the [Expo app QR](https://expo.dev/@aadrianleo/react_native_Jobbox?serviceType=classic&distribution=expo-go)
#
## Installation for developement

1. Install the npm packages :

  Run command : `npm install`

2. Insert you JSearch API key in the code.

You can get the JSearch API key from [RapidApi Jsearch](https://rapidapi.com/letscrape-6bRBa3QguO5/api/jsearch/) website. In the CodeSnippets in headers as 

`X-RapidAPI-Key : "Your_API_Key"`

Open the below 2 file path : 

```bash
hooks > useFetch.js
# and
app > search > [id].js
```

Update/Change your api key in the code : `"X-RapidAPI-Key": 'Your_API_Key'`,

3. Run the below command to start the app:

`expo-cli start --tunnel`

4. Open the expo go app in your mobile scan the QR code generated in the terminal wait for the app to get build.

5. Your app is ready 
#

Please let me know if you find something missing or any error.

Have Fun.😉 


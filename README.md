### Cognitive-Speech-STT-ServiceLibrary

## Closed Captioning Creator

Go here for How-to: https://docs.microsoft.com/en-us/azure/cognitive-services/speech/getstarted/getstartedcsharpservicelibrary

Subscribe to the Speech Recognition API, and get a free trial subscription key
The Speech API is part of Cognitive Services (previously Project Oxford). You can get free trial subscription keys from the Cognitive Services subscription page. After you select the Speech API, select Get API Key to get the key. It returns a primary and secondary key. Both keys are tied to the same quota, so you can use either key.

## Step 1: Install the sample application
Start Visual Studio 201x, and select File > Open > Project/Solution.

Double-click to open the Visual Studio 201x Solution (.sln) file named SpeechClient.sln. The solution opens in Visual Studio.

## Step 2: Build the sample application
Press Ctrl+Shift+B, or select Build on the ribbon menu. Then select Build Solution.

## Step 3: Run the sample application
After the build is finished, press F5 or select Start on the ribbon menu to run the example.

Open the output directory for the sample, for example, SpeechClientSample\bin\Debug. Press Shift+Right-click, and select Open command window here.

Run `SpeechClientSample.exe` with the following arguments:

Arg[0]: Specify an input audio WAV file.
Arg[1]: Specify the audio locale.
Arg[2]: Specify the recognition modes: Short for the `ShortPhrase` mode and Long for the `LongDictation` mode.
Arg[3]: Specify the subscription key to access the speech recognition service.

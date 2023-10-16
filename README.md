# Real-Time-Voice-Translation
it was a short college project , overview of this project is just to make a "voice translation" interface using voice only. 


Read.md

: Project Name - Real Life Voice Translation :


The most common form of communication between humans is Speech and communication plays a key role for delivering information. The fact is that every particular individual in the world will not have conversation in same language, many individuals will be speaking in many different languages. Summarizing the required content and delivering correct message is very much important.

If the information required is not delivered properly than many complications may occur. If either side of the communicating persons is unaware about the language then the cycle of speech will be incomplete. Hence we need a system that will solve our language barrier issue. So we came up with a system i.e. "Real Time Voice Translation" which will convert speech of one language into another language using python.

Although the translation services today provide a robust trained model with reasonable results and latency, the advent of globalisation demands for a better translation system. This serves as a breeding ground for a deeper research into the training of translation models and their architectures.

The project is titled as “Real Time Voice Translation”. The system will provide us the source to understand unknown language information by converting it into our required language. This project uses python for conversion of one language audio into another language audio. Google trans, speech_recognition, gtts, playsound are the main properties that are to be used in this project. Consider there is a video in a particular language that is not understood by a user ,and user wants to access the information in that video, so by our system we can access the required content , so we need to select the output language i.e. language that the user can understand and convert it using python. Conversion will be done using various functions such as Recognizer (),Translator(),listen()



** 

The main aim of this project is to convert the language spoken by a person into another language audio .For that initially we need to give voice input .consider that we are giving our voice input in Hindi language and we need output language as English. what the system will do is initially it will enable the microphone. Then by using recognizer. listen() it will recognize our voice and store in variable “voice”. Then the recognized input voice will be converted into text using “recognizer. recognize_google()” and converted text will be stored in “text” variable. This is what happens in “Convert Speech to Text” block.

Next we will be using Google Translate to convert this input text into text of output language i.e. English. Now the output text has been obtained now we have to convert this output text into speech form. We will be using gtts.gTTS() to convert the output text into speech. We will save this audio output in an mp3 file. Then we will use playsound. playsound() to play the audio output obtained .This is what basically happens in “convert text to speech” block. Then audio output will be obtained.

After fulfilled the requirements the projected mp3 file will be removed by itself, by 
using os.remove (‘captured_voice.mp3’)                                                                                               
In summary, our group hope that this program can bring benefits to a lot of people, especially for those who are very busy with their tasks and expecting to finish them all within a short time. By using this program, not only can we multitask, but we can also translate the speech that had been converted into text, to another language.

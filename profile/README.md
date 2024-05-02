## Inspiration
We get and share a lot of information through conversations in our daily lives. Not only that, but conversations are also the most effective way to understand yourself and the other person. But conversations are more easily forgotten in our minds than we think. Sometimes they are interpreted or distorted in their own way. Recording is the most basic way to record a conversation, but how much time do we have to spend listening to Recording again?

Through 🎙️*MinuteTaker AI*🚀, we want to create an effective and smart solution that can record and understand all kinds of conversations.

## What it does
🎙️*MinuteTaker AI*🚀 is a combination of Recording and Generative AI technology. Going beyond the Recording function, which was simply recording voices, MinuteTakser AI converts Speech into Text and extracts and summarizes the key parts. Furthermore, the user will get a chatbot tailored to this given conversation. By chatting interactively, the user can get not only information about the conversation but also surrounding knowledge to help them understand easily and much better.

## How we built it
We have developed the web version of 🎙️*MinuteTaker AI*🚀 for this time. The backend and frontend were developed based on Python and JavaScript languages, respectively. It is noteworthy that the core process was implemented using various APIs provided by Google.

- [**Google Cloud Speech**](https://cloud.google.com/python/docs/reference/speech/latest): This service utilizes the speech-to-text API to generate a conversation transcript and clusters the words spoken by each speaker.
- [**Google Vertex AI**](https://cloud.google.com/vertex-ai/docs/python-sdk/use-vertex-ai-python-sdk): It summarizes the conversation transcript and generates answers for user questions related to the conversation.
- [**Google Cloud Storage**](https://cloud.google.com/python/docs/reference/storage/latest): This component saves the processed results of each conversation into a Google bucket, which can then be used for the result-sharing function.



### Back-end

- [**LangChain**](https://python.langchain.com/docs/get_started/introduction): It is an open-source LLM orchestration framework to build Retrieval Augmented Generation(RAG) environment.
- [**chromadb**](https://www.trychroma.com/): It is a AI-native open-source vector database embedding documents and quries.
- [**librosa**](https://librosa.org/doc/main/index.html) and [**ffmpeg**](https://pypi.org/project/ffmpeg-python/): These libraries are used to verify audio files into the same form and create audio samples by trimming.


### Front-end
- [***Material UI***](https://mui.com/material-ui/): It is a open-source React component library that implements Google's Material Design.
- [***react-voice-recorder***](https://www.npmjs.com/package/react-voice-recorder): This component provides the UI service to record user voice as audio.
- [***react-markdown***](https://www.npmjs.com/package/react-markdown/v/8.0.6): It renders and visualize the summary contents into the markdown form.


## Challenges we ran into

1. ***Conversation Retention***: Conversations are valuable sources of information, but they often fade easily from our memory. We aim to retain and preserve these conversations by recording, converting speech into text, and summarizing key points.

2. ***Time Efficiency***: Traditional methods of taking meeting notes are time-consuming and error-prone, which can hinder productivity and delay decision-making. Even though people can use the recording, we should sift through lengthy recordings. Our streamlined recording process extracts essential information, enabling users to quickly review relevant content without listening to lengthy recordings.

3. ***Enhancing Understanding***: The LLM model-based chatbot not only provides answers about the conversation but also serves as an educational resource. By offering relevant information and context, helps users deepen their understanding of the conversation and related topics. Users can expand their knowledge through interactions with the chatbot.

4. ***Distortion and Interpretation***: Conversations can be misinterpreted or distorted over time. By providing accurate transcriptions and consistent summaries, we help prevent this distortion and ensure that the original intent is preserved. With the public link at the end of the process, your conversation can be shared with your friends or colleagues without any interference.

## Accomplishments that we're proud of

1. ***Realized our unique idea with Generative AI***

    We've tackled real-world problems faced in our daily conversation and Generative AI helps our solution become real.

2. ***Robust Implementation***

    The execution of our idea showcases our development skills. We've meticulously implemented the solution, ensuring it functions seamlessly.

3. ***Business Value***

    Our app has significant potential for businesses. By streamlining conversations and preventing information loss, can enhance productivity and decision-making.

4. ***Community Impact***

    We believe our app will drive positive change within the community. Whether in business meetings, debates, interviews, or monologues, it empowers users to communicate effectively.

5. ***Leveraging Google Cloud Services***

    We've harnessed the power of Google Cloud Services to build our solution. Specifically, we've utilized GCP Storage, the Speech API, and Vertex AI to create a robust and efficient application.


## What we learned

### General Insights

- **Exploring Generative AI:** Our journey with this project allowed us to delve into the exciting world of generative AI. By creating an application powered by cutting-edge technology, we've positioned ourselves at the forefront of market trends.

### Backend Development Lessons

- **Leveraging Gemini:** We harnessed the power of Gemini as a developer, beyond the normal user of Gemini Chat. Through prompt engineering and implementing the RAG framework, we enhanced the capabilities of the generative AI model and tailored it to our purpose.

- **Google Cloud Integration:** Transforming our idea into a real-world application required seamless integration with cloud services. We learned how to connect various Google Cloud components, including Google Cloud Storage, Google Cloud Speech, and Vertex AI.

### Frontend Development Insights

- **Effective Library Integration:** Our frontend development journey involved integrating diverse libraries such as React and Material-UI. These choices significantly boosted productivity and contributed to an enhanced user experience (UI/UX).

- **Responsive Design:** By combining React's conditional rendering with Material-UI's components (following Google's Material design principles), we achieved dynamic and responsive application design.

## What's next for MinuteTakerAI

Our current prototype represents a significant milestone, but there's much more to achieve to make a real impact within the community with 🎙️*MinuteTaker AI*🚀. Let's explore the next steps:

1. **Expanding UI Accessibility to Mobile Platforms:**
   - While our current version is web-based, we recognize its limitations in terms of portability. Conversations can occur anytime and anywhere, so we aim to create a mobile-friendly UI. This will allow users to effortlessly record and summarize conversations on their mobile devices.

2. **Enhancing AI-Supported Features:**
   - Leveraging our AI core, we plan to extend the application's capabilities. Consider features like sentiment analysis and automated topic detection. These enhancements will provide users with deeper insights into their conversations.
   - Additionally, offering customizable summary templates will enhance user satisfaction and adaptability.

3. **Addressing Security Concerns:**
   - Before going public, we must prioritize security. Implement robust file protection mechanisms to safeguard user data.
   - Detect and prevent unethical usage, ensuring that MinuteTakerAI remains a trusted tool.

4. **Overcoming API Performance Limitations:**
   - While building our application, we encountered performance limitations with Google AI-related APIs. Specifically, the Google Cloud Speech API had its challenges.
   - We've reported these issues through the Feedback Submission process and hope for a thorough review.

5. **Balancing Achievements and Continuous Improvement:**
   - We're proud of our achievements so far, but we remain open to feedback. By listening to advice from Google's engineers, we'll refine and enhance our solution.
   - Our ultimate goal is to intelligently address conversation recording challenges using AI technology, benefiting the wider community.

In summary, 🎙️*MinuteTaker AI*🚀 is poised for growth. We'd like to continue this journey, learn from feedback, and contribute to a more efficient and connected world!

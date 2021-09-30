# Emoz


Objective
In this project, we would be combining multiple services and open-source tools to make a
Chatbot that recommends songs based on the tone of the conversation which the user is
having with the chatbot.


Project Context
The purpose of chat bots is to support and scale business teams in their relations with
customers. It could live in any major chat applications like Facebook Messenger, Slack,
Telegram, Text Messages, etc. Chatbot applications streamline interactions between people
and services, enhancing customer experience. At the same time, they offer companies new
opportunities to improve the customers engagement process and operational efficiency by
reducing the typical cost of customer service. This project is focussed on building a custom
chatbot that will be your fundamental step of the learning curve of building your own
professional chatbots.

But you must be tired of the weird chat bots out there in the world which are made for
mainly business purposes? In this project, we would be building an extensive Chatbot
service, to which you can talk to. And talking to a chatbot wouldn't be business-driven. It
would just be casual conversations. Further, on top of it, the chatbot would also be
recommending songs to the user based on the tone of the user. This song recommendation
feature employs the use of Last.fm API, very much similar to the popular Spotify API. Also
for tone/emotion analysis of the conversation we will be using the IBM Tone Analyzer API.
Collaborating with these types of APIs is very much critical as in today's world the popular
chatbots do much more than simply having a data-driven conversation; to supplement
additional user-oriented features. Also the reason to choose python to build the chatbot is
because python boasts a wide array of open-source libraries for chatbots, including
scikit-learn and TensorFlow. It is great for small data sets and more simple analyses; also
Python's libraries are much more practical.


High-Level Approach
• User starts the conversation
• Emotional Analysis of the conversation is done using the IBM Emotional API
• Get the reply to the conversation from the Cakechat Chatbot
• Based on the Emotion which the app perceives, top songs are retrieved using Last.fm
songs API
• If a user listens to a particular song for some time, a similar song would be
recommended to the user using Last.fm API.


Primary goals
• Setting up an open-source project locally and handling the errors being faced
• Using multiple services to build up a new service over them.
• Having a real-world chatbot, to which you can literally chat like you chatting to a real
person and enjoying the music recommended by the system.


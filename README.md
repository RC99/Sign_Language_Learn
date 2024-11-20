# Be My Voice

### **Breaking Barriers, Building Connections**

Be My Voice is an innovative accessibility solution designed to empower individuals with speech disabilities by enabling real-time communication and learning opportunities. Our platform promotes inclusivity, allowing everyone to connect, learn, and share their voices with the world.

---

## **Inspiration**
When we saw the Accessibility track during SoCal Tech Week 2024, we knew we could make a difference. Our goal with *Be My Voice* is to break down communication barriers for those with speech disabilities. By integrating real-time ASL (American Sign Language) translation and ASL learning flashcards, we aim to empower individuals to pursue opportunities, build relationships, and express themselves freely.

---

## **Features**
1. **Real-Time ASL Translation**  
   Utilize a trained AI model to interpret ASL gestures in real-time using a laptop camera.
   
2. **ASL Flashcards for Learning**  
   Interactive flashcards provide simple, universal vocabularies to help users learn and understand ASL on the go.

---

## **Tech Stack**
- **Frontend**: JavaScript, HTML, CSS, Bootstrap  
- **Middleware API**: Flask  
- **Backend**: Python (OpenCV, Mediapipe, TensorFlow)  
- **Additional Tools**: OpenAI (ChatGPT 3.5 Turbo), Socket.IO  

---

## **How We Built It**
1. **Model Training**  
   - Utilized Python libraries like TensorFlow, Mediapipe, and OpenCV to train a Computer Vision model with custom ASL datasets.
   - Captured hundreds of images representing ASL vocabularies, overcoming the challenges of limited datasets.

2. **Integration**  
   - Flask was employed as the middleware to connect the frontend and backend seamlessly.  
   - ChatGPT 3.5 Turbo enhanced the system by expanding contextual meanings of ASL vocabularies, helping users better understand hand gestures.

3. **Frontend Development**  
   - Designed using Bootstrap for a responsive and user-friendly interface.
   - Leveraged JavaScript and Socket.IO to handle real-time communication and interaction.

---

## **Challenges**
- **Time Constraints**  
  Initially, we aimed to build a React Native app for iOS, Android, and web. However, we pivoted to a web-based solution due to time limitations.  
- **Dataset Limitations**  
  - Public datasets were inconsistent and incomplete for our needs.  
  - We created a custom dataset, taking hundreds of photos and learning ASL gestures in the process.  
- **Hardware Limitations**  
  Training the model on non-static time-series gestures was computationally intensive, leading to hardware challenges.

---

## **Accomplishments**
- Trained a real-time ASL model with acceptable accuracy despite hardware and time limitations.  
- Developed a robust tech stack integrating Computer Vision, AI, and web technologies.  
- Fostered teamwork and gained valuable insights into ASL and accessibility solutions.

---

## **What We Learned**
- **American Sign Language (ASL)**: Understanding ASL’s complexity, particularly non-static gestures.  
- **AI Challenges**: Training non-static time-series models is computation-intensive and hardware-dependent.  
- **Collaboration**: Building a solution that bridges Computer Vision, AI, and web development requires adaptability and teamwork.

---

## **What's Next**
- Improve the model to handle non-static ASL gestures effectively.  
- Expand the ASL vocabulary and improve the flashcard experience.  
- Explore cross-platform mobile app development to make *Be My Voice* more accessible.

---

## **Video**
- https://youtu.be/JZcFljUSWZE?feature=shared

---

## **Built With**
- **Languages**: Python, JavaScript, HTML, CSS  
- **Libraries/Frameworks**: Flask, TensorFlow, Mediapipe, OpenCV, Bootstrap  
- **Tools**: OpenAI, Socket.IO, Pygame  

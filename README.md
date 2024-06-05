# UOC Q&A App

## IT3003 - Advanced Programming Techniques

### Introduction

In a time where information and collaboration are essential, the need for efficient and reliable platforms to exchange knowledge is much higher. The “UOC Q&A App” addresses this challenge by transforming the way university students seek and share their expertise. Traditional search engines might offer a broad overview but often lack the context and nuance that only subject matter experts can provide. Our app fills this gap by creating an expert network and enabling collaborative learning. These are achieved through a seamless sign-up and sign-in process.

Our app will be developed using Java and XML in Android Studio, combining robust programming with versatile user interface design. Java will serve as the backbone for the app's logic and functionality, while XML will define the visual layout and structure of the user interface. We will use Firebase as the database for our app.

### User Actions

- **Actor: User**
  - **Sign In**: Log in to the app using credentials.
  - **Sign Up**: Create a new account by providing necessary information.
  - **Ask Question**: Post questions on various topics.
  - **Post Answer**: Answer questions posted by others.
  - **Edit Answer**: Edit their answers to improve accuracy and relevance.
  - **Rate Answer**: Rate the answers provided by other users.
  - **Access Questions**: Access questions asked by others for viewing, replying, or discussing.

### System Responses

- **Actor: UOC Q&A App**
  - **Authenticate User**: Authenticate user credentials during Sign In.
  - **Create User Account**: Create a new user account during Sign Up.
  - **Submit Question**: Process and store the user's posted question.
  - **Submit Answer**: Process and store the user's posted answer.
  - **Edit Answer**: Update the user's answer after editing.
  - **Rate Answer**: Record and display user ratings for answers.
  - **Retrieve Questions**: Retrieve and display questions for user access.

### Use Case Diagram

You can view the use case diagram designed using Drawio at the following link:
[Drawio Diagram](https://app.diagrams.net)

<img width="668" alt="Screenshot 2024-06-05 at 20 36 57" src="https://github.com/SachithMadhushanka/UOC-QandA-App/assets/131949127/085a5f0b-b19b-4fb9-8ec1-f524533333b6">

### Design

The Figma designs we plan to use as the basis for developing the UOC Q&A App can be found at the following link:
[Figma Design](https://www.figma.com/file/BddyMAUg1Yh5s0krA0047G/Group-Project?type=design&node-id=0%3A1&mode=design&t=tnzRW1CCYZgO2RUo-1)

<img width="766" alt="Screenshot 2024-06-05 at 20 37 20" src="https://github.com/SachithMadhushanka/UOC-QandA-App/assets/131949127/dca32104-cf39-41d0-b099-c30d026f60dd">


### Installation Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/uoc-qa-app.git
   cd uoc-qa-app
   ```

2. **Set Up Android Studio**:
   - Download and install [Android Studio](https://developer.android.com/studio).
   - Open the project in Android Studio.
   - Sync the project with Gradle files.

3. **Configure Firebase**:
   - Create a new Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Add your Android app to the Firebase project.
   - Download the `google-services.json` file and place it in the `app` directory.
   - Enable Authentication and Firestore Database in Firebase.

4. **Run the App**:
   - Connect your Android device or use an emulator.
   - Click on the "Run" button in Android Studio.

### Usage Instructions

1. **Sign Up**: Create a new account with your university credentials.
2. **Sign In**: Log in with your credentials to access the app.
3. **Ask Question**: Post your questions on various topics.
4. **Post Answer**: Provide answers to questions posted by others.
5. **Edit Answer**: Edit your answers for better accuracy and relevance.
6. **Rate Answer**: Rate the answers provided by other users to help highlight the best responses.
7. **Access Questions**: Browse and view questions asked by others, participate in discussions.

### Contribution Guidelines

1. **Fork the Repository**:
   - Click the Fork button in the repository.
2. **Clone Your Fork**:
   ```bash
   git clone https://github.com/yourusername/uoc-qa-app.git
   cd uoc-qa-app
   ```
3. **Create a New Branch**:
   ```bash
   git checkout -b feature-branch
   ```
4. **Commit Your Changes**:
   ```bash
   git commit -m 'Add some feature'
   ```
5. **Push to the Branch**:
   ```bash
   git push origin feature-branch
   ```
6. **Open a Pull Request**:
   - Go to the repository in GitHub and click "New Pull Request".

### License

This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgements

- [Android Studio](https://developer.android.com/studio)
- [Firebase](https://firebase.google.com/)
- [Drawio](https://app.diagrams.net)
- [Figma](https://www.figma.com/)

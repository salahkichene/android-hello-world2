# Android Hello World Project

This is a simple Android application named "Aggretsuko" developed as part of the Nuevas Tecnologías 2 course. The application showcases basic Android development practices, including UI design, resource management, and testing.

## Project Structure

The project is organized as follows:

```
android-hello-world2
├── .github
│   └── workflows
│       └── android-deploy.yml
├── app
│   ├── .gitignore
│   ├── build.gradle
│   ├── proguard-rules.pro
│   └── src
│       ├── androidTest
│       │   └── java
│       │       └── com
│       ├── main
│       │   ├── AndroidManifest.xml
│       │   ├── java
│       │   │   └── com
│       │   └── res
│       │       ├── drawable
│       │       ├── drawable-v24
│       │       ├── layout
│       │       ├── mipmap-anydpi-v26
│       │       ├── mipmap-hdpi
│       │       ├── mipmap-mdpi
│       │       └── values
│       └── test
│           └── java
└── README.md
```

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/android-hello-world2.git
   cd android-hello-world2
   ```

2. **Open the Project**
   Open the project in Android Studio or your preferred IDE.

3. **Build the Project**
   Use the following command to build the project:
   ```bash
   ./gradlew build
   ```

4. **Run the Application**
   You can run the application on an emulator or a physical device.

## Usage

The application displays the title, author, and subject of the project. You can modify the strings in `res/values/strings.xml` to customize the displayed information.

## Testing

The project includes unit tests located in the `app/src/test/java` directory and instrumentation tests in the `app/src/androidTest/java` directory. You can run the tests using the following command:
```bash
./gradlew test
```

## Deployment

The project is configured to deploy the APK using GitHub Actions. The workflow file is located at `.github/workflows/android-deploy.yml`. Make sure to configure the necessary secrets and settings in your GitHub repository for deployment.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
### 1. Download Java Development Kit (JDK)

  - Visit the Oracle [Java Downloads](https://www.oracle.com/java/technologies/downloads)
  - Choose the version you want (e.g., Java 17 is the latest LTS version as of now)
  - Download the appropriate installer for your operating system (Windows, macOS, or Linux)

### 2. Install the JDK

On Windows

  - Run the installer you downloaded
  - Follow the on-screen instructions
  - Note the installation directory (e.g., C:\Program Files\Java\jdk-XX.X.X)

### 3. Configure Environment Variables

On Windows

  - Open Control Panel > System > Advanced system settings
  - Go to the Advanced tab and click Environment Variables
  - Under System Variables, find Path and click Edit
  - Add the bin directory of your JDK installation (e.g., C:\Program Files\Java\jdk-XX.X.X\bin)
  - Create a new variable JAVA_HOME and set its value to the JDK installation directory (e.g., C:\Program Files\Java\jdk-XX.X.X)

### 4. Verify the Installation

  - Open a terminal or command prompt
  - Run
    
      ```bash
      java -version
      ```

  You should see the installed Java version

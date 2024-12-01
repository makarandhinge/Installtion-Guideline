
## For Windows

1. Download Maven
- Visit the official [Apache Maven website.](https://maven.apache.org/download.cgi)
- Download the binary zip archive (apache-maven-version-bin.zip).
2. Extract the archive
- Extract the contents of the zip file to a directory on your machine, e.g., C:\Program Files\Apache\maven-version.
3. Set environment variables
- Open System Properties → Advanced system settings → Environment Variables.
- In System variables, click on New:
  - Name: MAVEN_HOME
  - Value: the path to your Maven folder (e.g., C:\Program Files\Apache\maven-version).
- Find the Path variable in System variables, and click Edit. Add the - Maven bin directory to the path (e.g., C:\Program Files\Apache\maven-version\bin).
4. Verify installation:
- Open a Command Prompt and type
  ```bash
  mvn -v
- You should see the Maven version information.

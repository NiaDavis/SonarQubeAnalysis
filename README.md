## SonarQube Analysis

This project uses SonarQube to ensure code quality and cleanliness.

### Running SonarQube Analysis

1. Ensure SonarQube is running locally:
    ```bash
    ./sonar.sh start
    ```

2. Run the SonarQube analysis:
    ```bash
    mvn sonar:sonar
    ```

3. Access the SonarQube dashboard at `http://localhost:9000` to view the analysis results.

### Fixing Issues

1. Review the issues reported by SonarQube.
2. Make the necessary code changes.
3. Re-run the SonarQube analysis to ensure all issues are resolved.

# GitHub Actions demo

<b>Workflow for Veracode SAST Scan demo.</b><br/><br/>
<b>veracode-sast-scan-demo.yml</b> - This is a static scan. It does the following things - 
1. Take checkout of the repository.
2. Setup Java version 11 in the runner.
3. Generate the build number using GitHub action.
4. Prints the build number generated above.
5. Generating and pushing the tag info to GitHub. 
6. Builds the Spring Boot maven project.
7. Download the Java API wrapper which is used for scanning Java based projects.
8. Upload the artifacts to Veracode and trigger static scan.

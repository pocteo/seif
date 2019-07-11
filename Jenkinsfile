
#!/usr/bin/env groovy

stage("Unit Tests") {
  git(url: "https://github.com/pocteo/seif.git", branch: "${ghprbSourceBranch}")
  sh "npm install"
  sh "npm test"
}

# first-github-action
:eye: A simple github action build for the github hackathon that greets the user when they do commits and PRs.

copy and paste these code to your main.yml in newly created workflow

```


name: well-wisher-1.0
on: push

jobs:
  build:
    name: well-wisher
    runs-on: ubuntu-latest
    steps:
      - uses: Aman-zishan/first-github-action@v1
        with:
          MY_NAME: "<YOUR_NAME>"
 ```

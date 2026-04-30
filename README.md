There are three files under src:

```
src
├── actually_plain_text.json
├── real_json.json
└── this_is_the_issue.json
```

Only two of them show in
[SQC](https://sonarqube.us/code?id=sonar-eval_json-repro&selected=sonar-eval_json-repro%3Asrc):

```
actually_plain_text.json
real_json.json
```

I have also tried with a json and a stray comma and it also shows, so it
is not just "any" malformed json file dissapears. It has to be this specific
syntax error.

# tam-integration-onsite
## Instructions
1. [Install fossa-cli](https://github.com/fossas/fossa-cli#installation)
2. Clone this repo to your local machine
3. Run `npm install` to download all relevant dependencies
4. Run `fossa analyze --output` to print analysis results locally (feel free to pipe results to a utility such as `jq` to better format the results)
5. Review the results and work with the interviewer to reverse engineer the dependency path of a single deep dependency
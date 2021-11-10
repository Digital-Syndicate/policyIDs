# policyIDs

Digital Syndicate's CNFT Verified Policy Database
This repository is using the CNFT.io policy standard

To add your project to the list of verified policies for the marketplace:

Important: You must show proof of your project by tweeting your pull request to your projects twitter and linking in your pull request Alternatively, provide adequate proof such as a direct link to project website with policies

Make a pull request to add a file to the repository in this format.

Information:

project: Name of your project

policies one or many policy ids of your project

https://www.youtube.com/watch?v=z6yPjed4sMI

Validate your code before requesting: https://jsonformatter.curiousconcept.com/#

Single Project:

[
  {
    "project": "YourFirstProjectName",
    "policies": [
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab"
    ]
  }
]
Multiple Projects under one name:

[
  {
    "project": "YourFirstProjectName",
    "policies": [
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab"
    ]
  },
  {
    "project": "YourSecondProjectName",
    "policies": [
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab",
      "abcdefghijkklmnopqrstuvwxyzabcdefghijkklmnopqrstuvwxyzab"
    ]
  },
]

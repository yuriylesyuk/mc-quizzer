# mc-quizzer
Multiple-choice Style Quizz for Foreign Languages

The mc-quizzer is a javascript application that combines images, words, and sounds 
in an integrated experience. 
The voice clips are generated using the Google Translate.

The design goal was to minimise an amount of mouse clicks while working with the quizz.

The quizz is data driven using .json file like:
```json
{ "qSet":
  [
    { "question": "the body", "answer": "le corps", "image": "https://docs.google.com/uc?id=0B4yq2fq6lfDhNTllOTBjZmEtZWU2ZC00YTJlLTk0NDMtOWM5MDc1ZTNkMzk1", "audio": "https://docs.google.com/uc?id=0B4yq2fq6lfDhZTc3YzU4MjQtNDQ3ZS00Mjk5LWFlNjEtZGY4MTA0NTFhNDdj"  }
,    { "question": "the head", "answer": "la tête", "image": "https://docs.google.com/uc?id=0B4yq2fq6lfDhZTU0ZWI3YjAtMDJlMy00MGYzLWI3NjItMzM0NDc5OWVjMmZm", "audio": "https://docs.google.com/uc?id=0B4yq2fq6lfDhYTkzYTY5ODYtYmEwZi00NjkxLThjZDctOWY3ZTI2NDYzNjQy"  }
,    { "question": "the hair", "answer": "les cheveux", "image": "https://docs.google.com/uc?id=0B4yq2fq6lfDhMTc1OWZmYzQtN2IwZS00YmNiLWE0MTgtNmYwNjVjM2M3YzY3", "audio": "https://docs.google.com/uc?id=0B4yq2fq6lfDhYTM5MGQ2MjctODMzOC00NTgzLTllZmQtMTBlY2E3NzJkYTlh"  }
 ]
}
``` 

The application is deployed at: <http://mc-quizzer.appspot.com/mcq.html>

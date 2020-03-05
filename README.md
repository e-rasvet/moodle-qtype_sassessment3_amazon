Question type sassessmentamazon, Amazon Transcribe version
----------------------

It is Speech Assessment question type. You can add video questions with subtitles.



###Installation

You can keep a copy of the sassessmentamazon in Moodle in the question/type/ folder and as long as it is called sassessmentamazon the plug in will
be ignored.
Rename folder to "sassessmentamazon"


####Installation Using Git 

To install using git for the latest version (the master branch), type this command in the
root of your Moodle install:

    git clone git://github.com/e-rasvet/moodle-qtype_sassessmentamazon.git question/type/sassessmentamazon
    echo '/question/type/sassessmentamazon' >> .git/info/exclude

####Installation From Downloaded zip file

Alternatively, download the zip from :

* latest (master branch) - https://github.com/e-rasvet/moodle-qtype_sassessmentamazon/zipball/master

unzip it into the question/type folder, and then rename the new folder to sassessmentamazon.

####How to get Amazon Transcribe Access key

1. You need to sign up amazon transcribe account:
https://portal.aws.amazon.com/billing/signup#/start
2. Login.
3. Go to AWS IAM console https://console.aws.amazon.com/iam/home#/home
4. Create new user
5. Give new user role "AmazonTranscribeFullAccess"
6. And create new access key: User -> click to username -> Security
credentials -> Create access key.

 


@copyright  Igor Nikulin, Paul Daniels, Nobuhiro Kumai
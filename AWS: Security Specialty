# aws-cert-notes

## Resources:

-   [Encryption and Key Management in AWS - YouTube](https://www.youtube.com/watch?v=uhXalpNzPU4)
-   [Advanced Security Best Practices Masterclass - YouTube](https://www.youtube.com/watch?v=zU1x5SfKEzs)
-   [Automating_Governance_on_AWS  - Whitepaper](https://d1.awsstatic.com/whitepapers/compliance/Automating_Governance_on_AWS.pdf)
-   [AWS_Answers_to_Key_Compliance_Questions - Whitepaper](https://d1.awsstatic.com/whitepapers/compliance/AWS_Answers_to_Key_Compliance_Questions.pdf)
-   [The DDoS Whitepaper](https://d1.awsstatic.com/whitepapers/Security/DDoS_White_Paper.pdf)
-   [AWS KMS best practices - Whitepaper](https://d1.awsstatic.com/whitepapers/aws-kms-best-practices.pdf)
-   [Using Policy Conditions with AWS KMS - AWS Key Management Service](https://docs.aws.amazon.com/kms/latest/developerguide/policy-conditions.html)
-   [Importing Key Material in AWS Key Management Service (AWS KMS) - AWS Key Management Service](https://docs.aws.amazon.com/kms/latest/developerguide/importing-keys.html)
-   [AWS re:Invent 2018: [REPEAT 1] Become an IAM Policy Master in 60 Minutes or Less (SEC316-R1) - YouTube](https://www.youtube.com/watch?v=YQsK4MtsELU)
-   [AWS re:invent 2017: Best Practices for Implementing AWS Key Management Service (SID330) - YouTube](https://www.youtube.com/watch?v=X1eZjXQ55ec)
-   Linux Academy AWS: SS course

## Practice exams:

-   [AWS Readiness exam](https://www.aws.training/Details/eLearning?id=34786)
-   [Whizlab's AWS Certified Security Specialty Practice Exams](https://www.udemy.com/course/whizlabs-aws-certified-security-specialty-practice-tests/)
	- Just to note here, a few of the questions they give you aren't grammatically correct…

-   [Get Certified Practice Exams](https://www.udemy.com/course/scs-c01-aws-certified-security-specialty-practice-tests/)

## General notes from me about taking the exam:

-   KMS. Literally, everything about KMS. Understand:

	-   API endpoints necessary to encrypt/decrypt/re-encrypt
	-   How to import/re-import key material
	-   When AWS can automatically rotate keys
	-   Deletion policies
	-   Key policies associated with a Customer Master Key
	-   When KMS is a solution vs when Cloud HSM would be a solution

-   Cross account access, inside and out

	-   When to use trusted entities via IAM roles
	-   How to require an externalID via policy conditions
	-   When to use resource/identity policies

-   Understand the difference between AWS Config, Trusted Advisor, and Cloudtrail

	-   They try to trick you between the three
	-   When anything comes up about AUDITING CHANGES TO RESOURCES, it's probably AWS Config
	-   If they ask you about CHECKING FOR OPEN SECURITY GROUPS, OPEN BUCKETS, MFA ON ROOT ACCOUNT, ETC it's probably Trusted Advisor
	-   If they ask you about LOGGING API CALLS OR WHO DOES WHAT, that's probably Cloudtrail

-   What to do when an EC2 instance gets compromised

	-   Do not select anything about logging into the instance. Period.
	-   Do not terminate the instance, stop the instance
	-   Create an EBS Snapshot of the instance
	-   Change the security group to only allow *NECESSARY* traffic to investigate forensically
	-   Apply forensics to the EBS snapshot securely, in an isolated environment

-   Remember, it is best practice to use AWS accounts for individual applications/business units to reduce blast radius, this comes up a lot
-   There were usually two blatantly incorrect answers, and two answers that seem like they could be correct, with one of those being the correct answer
-   Sometimes, you'll get questions asking you about the property of an AWS service. Other questions on the test might actually *give* you the answer, so remember that when going through and flagging questions

![Table for KMS CMKs](https://i.imgur.com/glUiI08.png)
![enter image description here](https://i.imgur.com/xQ2TPui.png)

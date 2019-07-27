#Team Elect_tricks : Idea for the project
The main idea behind the project is to create a platform where a user/voter can vote from home/anywhere securely using blockchains so that the voting percentage can be increased which is nowadays a concern for the election commission.But there are some challenges or problems to think on,like
1.Confidentiality and integrity : The vote given cannot be changed or read by someone else.Also election commission also an read the vote but not the identity of the voter so that the annonymity of the user is also considered.
2.Non-repudiation : We don't want anyone to vote twice. 
3.Authentication : And we don't want someone to vote behalf of someone else.

Now here are the solution we found so far : 
1.Aadhar No. can be used as an unique identity so we can use Aadhar details to log in.
2.Though Aadhar is unique identity we don't want the annonymity of the user at risk so we will convert it into a HASHED KEY by using
  SHA-256/SHA-512 and that too will be encrypted with the public key of the election commission so that only election commission will be 
  able to see that vote by using their private key and also from one key we can accept only one vote so the voter is still annonymous for the commission and also
  voter can't vote twice.
3.Now for authentication,i.e. noone else can't vote on behalf of someone else we can use OTP verification and fingerprint verification as     well(The details are already with Aadhar to verify)
4.For more security we'll also record the IP-address with HASHED key.

So in this way we can make our election system more secure,more reliable and more convenient using Azure Blockchains.

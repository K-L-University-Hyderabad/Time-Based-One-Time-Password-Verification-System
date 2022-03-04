# Time-Based-One-Time-Password-Verification-System
  During the Covid-19 pandemic, almost all jobs and activities to be limited, relying on the internet network. Data security in an internet network is most important and needs to be a concern for internet users. 
  The internet network is a public network, which is vulnerable to security attacks. Attacks may occur to retrieve user data in the form of a username and password
OTP Verification is the process of verifying a user by sending a unique password so that the user can be verified before completing a registration or payment process. 
  Most of the time, we get an OTP when we make an online payment, or when we forget our password, or when creating an account on any online platform. 
Thus, the sole purpose of an OTP is to verify the identity of a user by sending a unique password.
  OTP is classified into two types : HOTP and TOTP
HMAC-based One-time Password algorithm (HOTP) is an event-based OTP where the moving factor in each code is based on  counter.
Time-based One-time Password (TOTP) is a time-based OTP where the moving factor in each code is based on time.
Every HOTP code is valid until it’s used, or until a subsequent one is validated by the server. So the chances for hacking are high.
TOTP is basically a branch of HOTP and it has a huge advantage over HOTP.
Unlike with HOTP, OTPs are generated using the number of time steps from Unix time. Usually, the time step is set to either 30 or 60 secs.
So when considering TOTP vs HOTP the obvious choice is TOTP, simply because it is more secure.

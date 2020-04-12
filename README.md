

[Try Restcomm Cloud NOW for FREE!](https://www.restcomm.com/sign-up/) Zero download and install required.


All Restcomm [docs](https://www.restcomm.com/docs/) and [downloads](https://www.restcomm.com/downloads/) are now available at [Restcomm.com](https://www.restcomm.com).



# RestComm Java SS7 Stack and Services

[![Join the chat at https://gitter.im/RestComm/jss7](https://badges.gitter.im/RestComm/jss7.svg)](https://gitter.im/RestComm/jss7?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bhttps%3A%2F%2Fgithub.com%2FRestComm%2Fjss7.svg?type=shield)](https://app.fossa.io/projects/git%2Bhttps%3A%2F%2Fgithub.com%2FRestComm%2Fjss7?ref=badge_shield)

## Introduction

Open Source Java SS7 stack that allows Java apps to communicate with legacy SS7 communications equipment. 

jSS7 provides an open source software solution implementing M3UA, SCCP, TCAP, CAMEL, MAP, ISUP protocols for a dedicated equipment (Dialogic) and also M3UA (SIGTRAN) over IP.

## How to create a working version

Install pre-requisites. Note openjdk-11-jdk won't work

sudo apt-get install openjdk-8-jdk
sudo apt install maven

Then you need to install SCTP and jss7 to your local maven repo, like this:

git clone https://github.com/doender17/sctp.git
cd sctp
mvn install -DskipTests

cd ..
git clone https://github.com/doender17/jss7.git
cd jss7
	
mvn install -DskipTests


# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to 
the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
![1sts](https://github.com/LOKESHKUMARARI/creating-a-backdoor-with-SET/assets/119406110/97c353f7-4e68-49d9-97a3-420c842d4654)

It displays the following menu and select 2 for Website Attack Vectors:
![Screenshot_2023-05-29_03_56_37](https://github.com/LOKESHKUMARARI/creating-a-backdoor-with-SET/assets/119406110/9d29880e-6f8a-4734-a61d-80a606cb64c7)
The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![Screenshot_2023-05-29_03_56_47](https://github.com/LOKESHKUMARARI/creating-a-backdoor-with-SET/assets/119406110/63a26518-1cee-4ceb-ac49-bf5eac8e91a9)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![Screenshot_2023-05-29_03_57_44](https://github.com/LOKESHKUMARARI/creating-a-backdoor-with-SET/assets/119406110/19e568d5-e3f1-46c8-b5e1-3380328a42f6)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![Screenshot_2023-05-29_03_57_57](https://github.com/LOKESHKUMARARI/creating-a-backdoor-with-SET/assets/119406110/7c403123-f29a-43e3-b43c-80274e7d3075)

It shows the following screen in which the option Google can be selected:

![Screenshot_2023-05-29_03_58_05](https://github.com/LOKESHKUMARARI/creating-a-backdoor-with-SET/assets/119406110/a9048408-ed80-4cf1-86d7-d0fc9d336b3d)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![Screenshot_2023-05-29_04_02_27](https://github.com/LOKESHKUMARARI/creating-a-backdoor-with-SET/assets/119406110/c777ee00-f0d5-4b4b-aa12-c0c79e7bf711)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/LOKESHKUMARARI/creating-a-backdoor-with-SET/assets/119406110/5a087533-d7cb-4a99-83cb-257f49bab68a)


SET logs the information regarding the Google credentials:

![l](https://github.com/praveenst13/creating-a-backdoor-with-SET/assets/118787793/569bac5b-8b6b-4f99-b679-bdf6e3878475)
SET logs the information in the xml file under /root/.set directory:
![Screenshot_2023-06-02_05_43_03](https://github.com/LOKESHKUMARARI/creating-a-backdoor-with-SET/assets/119406110/c7366d6d-37e3-44a7-a47e-d9f30abaa36b)







## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

## Configuring Active Directory on EC2 Virtual Machine
### Link to Loom

<https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847>
### Objective

This SOP outlines the steps to configure Active Directory on a provisioned EC2 virtual machine, ensuring a clear and efficient process for team members.

### Key Steps

**1. Open Server Manager** [0:00](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=0)

![image](https://github.com/franklopez7554/Configuring-Active-Directory-on-EC2-Virtual-Machine/blob/main/Screenshot%202025-07-02%20060616.png)

- Click on the Windows icon.
- Select 'Server Manager' from the menu.

**2. Add Roles and Features** [0:17](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=17)

![image](https://github.com/franklopez7554/Configuring-Active-Directory-on-EC2-Virtual-Machine/blob/main/Screenshot%202025-07-02%20060630.png)

- In Server Manager, click on 'Add Roles and Features'.
- Follow the prompts to collect data.

**3. Proceed with Installation** [1:05](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=65)

![image](https://github.com/franklopez7554/Configuring-Active-Directory-on-EC2-Virtual-Machine/blob/main/Screenshot%202025-07-02%20060643.png)
- Click 'Next' through the installation prompts until you reach the 'Active Directory Domain Services' option.

**4. Add Features** [2:53](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=173)

![image](https://github.com/franklopez7554/Configuring-Active-Directory-on-EC2-Virtual-Machine/blob/main/Screenshot%202025-07-02%20060716.png)

- Select 'Add Features'.
- Leave all settings as default and click 'Next' until you reach the 'Install' button.

**5. Complete Installation** [3:03](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=183)

![image](https://github.com/franklopez7554/Configuring-Active-Directory-on-EC2-Virtual-Machine/blob/main/Screenshot%202025-07-02%20060731.png)
- Click 'Install' and wait for the installation to complete.
- Once finished, click 'Close'.

**6. Promote Server to Domain Controller** [7:31](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=451)

![image](https://github.com/franklopez7554/Configuring-Active-Directory-on-EC2-Virtual-Machine/blob/main/Screenshot%202025-07-02%20060800.png)
- Click on 'Promote this server to a domain controller'.
- Choose 'Add a new forest' and enter 'school.local' as the root domain name.

**7. Set Password and Complete Configuration** [8:05](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=485)

![image](https://github.com/franklopez7554/Configuring-Active-Directory-on-EC2-Virtual-Machine/blob/main/Screenshot%202025-07-02%20060826.png)

- Set a password for the Directory Services Restore Mode.
- Click 'Next' through the remaining prompts until you reach 'Install'.

**8. Finalize Configuration** [8:50](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=530)

![image](https://github.com/franklopez7554/Configuring-Active-Directory-on-EC2-Virtual-Machine/blob/main/Screenshot%202025-07-02%20060852.png)

- Click 'Install' and wait for the server to configure.
- The server will restart and you will need to reconnect to it.

### Cautionary Notes

- Ensure that you have administrative privileges on the EC2 instance before starting the configuration.
- Be cautious with the password you set for the Directory Services Restore Mode; it should be secure and memorable.

### Tips for Efficiency

- Familiarize yourself with the Server Manager interface to navigate quickly.
- Keep a checklist of the steps to avoid missing any important configurations.
- Document any errors or issues encountered during the process for future reference.

# Configuring-Active-Directory-on-EC2-Virtual-Machine

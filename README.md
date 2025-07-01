## Configuring Active Directory on EC2 Virtual Machine

### Objective

This SOP outlines the steps to configure Active Directory on a provisioned EC2 virtual machine, ensuring a clear and efficient process for team members.

### Key Steps

**1. Open Server Manager** [0:00](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=0)

![generated-image-at-00:00:00](https://loom.com/i/135df26c71404692ae7c3765f26f4006?workflows_screenshot=true)

- Click on the Windows icon.
- Select 'Server Manager' from the menu.

**2. Add Roles and Features** [0:17](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=17)

![generated-image-at-00:00:17](https://loom.com/i/a7664a402e8d42b6b3f749f993c6b507?workflows_screenshot=true)

- In Server Manager, click on 'Add Roles and Features'.
- Follow the prompts to collect data.

**3. Proceed with Installation** [1:05](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=65)

![generated-image-at-00:01:05](https://loom.com/i/f8a2da60ee56475aa35f591a5aafffd8?workflows_screenshot=true)

- Click 'Next' through the installation prompts until you reach the 'Active Directory Domain Services' option.

**4. Add Features** [2:53](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=173)

![generated-image-at-00:02:53](https://loom.com/i/6511ad9356754539aa1ec357311b4de8?workflows_screenshot=true)

- Select 'Add Features'.
- Leave all settings as default and click 'Next' until you reach the 'Install' button.

**5. Complete Installation** [3:03](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=183)

![generated-image-at-00:03:03](https://loom.com/i/a94db9935cae4a00a4759e67107e1371?workflows_screenshot=true)

- Click 'Install' and wait for the installation to complete.
- Once finished, click 'Close'.

**6. Promote Server to Domain Controller** [7:31](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=451)

![generated-image-at-00:07:31](https://loom.com/i/7c2a4beac8994856ae41d2ca2c267af3?workflows_screenshot=true)

- Click on 'Promote this server to a domain controller'.
- Choose 'Add a new forest' and enter 'school.local' as the root domain name.

**7. Set Password and Complete Configuration** [8:05](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=485)

![generated-image-at-00:08:05](https://loom.com/i/20df796a42b74e9db80f58e8228cefe0?workflows_screenshot=true)

- Set a password for the Directory Services Restore Mode.
- Click 'Next' through the remaining prompts until you reach 'Install'.

**8. Finalize Configuration** [8:50](https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847?t=530)

![generated-image-at-00:08:50](https://loom.com/i/d9a68a5bdce344eda3dd54d7919dfa6d?workflows_screenshot=true)

- Click 'Install' and wait for the server to configure.
- The server will restart and you will need to reconnect to it.

### Cautionary Notes

- Ensure that you have administrative privileges on the EC2 instance before starting the configuration.
- Be cautious with the password you set for the Directory Services Restore Mode; it should be secure and memorable.

### Tips for Efficiency

- Familiarize yourself with the Server Manager interface to navigate quickly.
- Keep a checklist of the steps to avoid missing any important configurations.
- Document any errors or issues encountered during the process for future reference.

### Link to Loom

<https://loom.com/share/6e4d1ee0c3af447fb2e1d7f81f262847># Configuring-Active-Directory-on-EC2-Virtual-Machine

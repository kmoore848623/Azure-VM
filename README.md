![azure](https://github.com/kmoore848623/Azure-VM/assets/157086384/a201ff6e-e2fd-45c6-b406-224fb500be67)

# ☁️ Creating a Virtual Machine in Microsoft Azure

This walkthrough demonstrates how to deploy a Virtual Machine using Microsoft Azure — Microsoft’s cloud computing platform. By completing this lab, you'll learn how to set up and configure a VM through the Azure portal. This foundational skill is crucial for cloud computing, system administration, and cybersecurity roles.

---

## 🧰 Tools and Technologies Used

- Microsoft Azure Portal

---

## ✅ Prerequisites

- Microsoft Azure account

---

## 🚀 Deployment Steps

### 🛠️ Step 1: Create a Resource Group

1. Navigate to the [Azure Portal](https://portal.azure.com/).
2. Click **Resource groups** under Azure Services.

   ![Screenshot](https://github.com/kmoore848623/osticket-prereqs/assets/157086384/84dc2a56-ef25-4c7e-8e8e-6663e6b1c654)

3. Click **Create**.

   ![Screenshot](https://github.com/kmoore848623/osticket-prereqs/assets/157086384/6e2dca3c-f137-46a2-bcab-477272fc254e)

4. Enter a name for your resource group under **Project details**.
5. Choose a region under **Resource details**.
6. Click **Review + Create**, then **Create**.

   ![Screenshot](https://github.com/kmoore848623/osticket-prereqs/assets/157086384/f7551b32-16ba-45da-a487-d6c4dc2213ae)
   ![Screenshot](https://github.com/kmoore848623/osticket-prereqs/assets/157086384/ce98924e-930f-4564-8de8-16929274c726)

---

### 🖥️ Step 2: Create a Virtual Machine

1. In the [Azure Portal](https://portal.azure.com/), click **Virtual machines** under Azure Services.

   ![Screenshot](https://github.com/kmoore848623/osticket-prereqs/assets/157086384/7aa5268b-5e4b-4c71-bc54-4c9dfac8ad06)

2. Click **Create**, then select **Azure virtual machine**.

   ![Screenshot](https://github.com/kmoore848623/osticket-prereqs/assets/157086384/dae99beb-c6b5-471f-be99-1d6c69694049)

3. Select the same resource group you created earlier.
4. Choose your region and name your virtual machine.
5. Select a VM image (e.g., Windows 10).

   ![Screenshot](https://github.com/kmoore848623/osticket-prereqs/assets/157086384/46a0de79-461d-4d4b-a3ee-d2509cbb96fc)

6. Choose a VM size.
7. Set a username and password for the administrator account.
8. Click **Next** twice to navigate to the **Networking** tab.

   ![Screenshot](https://github.com/kmoore848623/osticket-prereqs/assets/157086384/adc0e245-b186-453c-86c5-8c600a733abb)

9. Azure automatically creates a virtual network, subnet, IP address, and network interface.
10. Click **Review + Create**, then **Create**.

   ![Screenshot](https://github.com/kmoore848623/osticket-prereqs/assets/157086384/e5c7caef-1677-4bf0-adc2-b6b3826a02ee)
   ![Screenshot](https://github.com/kmoore848623/osticket-prereqs/assets/157086384/c6dc410a-2f99-4042-b1fa-c9693557cf5c)

---

## 🧠 Summary

By following these steps, you've successfully:

- Created a Resource Group in Azure
- Deployed a Windows Virtual Machine
- Learned basic Azure networking and configuration concepts

This project provides a solid foundation in cloud infrastructure and prepares you for more advanced labs such as web hosting, VM security, and Azure automation.

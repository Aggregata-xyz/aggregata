# Access Aggregata Public Dataset

In Aggregata, you can assign a mount point folder path to create a public dataset that appears as a folder located in a Windows or Linux system.
> Configuring a local proxy in the settings before using this feature is recommended to avoid unstable speed for Mainland China.

---
## Before you start

If you are a Linux user, ensure you have installed and configured the fuse when using Ubuntu as:
```
sudo apt update
sudo apt install libsnappy-dev libfuse-dev -y
echo "user_allow_other" | sudo tee -a /etc/fuse.conf
```

## Mount a dataset as a folder
1. Click **Public Dataset** on the left;
2. Create a path for the mount point folder;
3. Click the checkbox to choose the dataset ;
4. Click **Mount**.

![image](https://github.com/Aggregata-xyz/aggregata/assets/158275971/1f577b7a-fe9b-4649-b1df-f5a52d887443)

The folder will be created on the assigned path. You can double-click on it to access its contents. You also have the option to access the dataset directly by using OS filesystem API.

## Unmount the dataset
When you finish using the dataset, you may want to unmount it.
Click the checkbox to choose the dataset ;
Click **Unmount**.

## Mount another dataset
You can mount up to one dataset at a time. Before mounting the new dataset, make sure to [unmount the previous dataset](#unmount-the-dataset) by following the steps mentioned above.




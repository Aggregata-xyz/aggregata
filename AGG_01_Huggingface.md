# Importing HuggingFace Project
Configuring a local proxy in the settings before using HuggingFace is recommended to avoid unstable speed for Mainland China.
## Function Description
We support resumes from breakpoint. If your download fails due to network fluctuation or block sealed timeout, you can click  **Pause All** first and then click **Start All** to resume from where you left off.

![image](https://github.com/Aggregata-xyz/aggregata/assets/158275971/e6873c45-fd48-4f3d-ae50-e5f5e224836a)

## Importing HuggingFace Models/Datasets
If you need to download a model/dataset that requires authorization or you need to be logged in to HuggingFace to download it, please [configure your HuggingFace account token](#configure-huggingface-account-token) as described in the following tutorial before downloading it.

Click on the HuggingFace button on the client page, enter the model/dataset link you want to download, and click **Browse** to access the list of related files. (NOTE: we use `https://huggingface.co/datasets/detection-datasets/coco` as example link)

![image](https://github.com/Aggregata-xyz/aggregata/assets/158275971/e424a1ac-44bb-47bd-83bc-5079f9ce67b5)

You can select the files by clicking the checkbox to the left of the file name, and you can also select the individual files and click Batch Import to import them.

![image](https://github.com/Aggregata-xyz/aggregata/assets/158275971/784b3792-b90d-4b96-a337-139d163079ea)

After completing the above steps, you can monitor the upload progress of the files in real time by clicking on the **Uploading** button.

![image](https://github.com/Aggregata-xyz/aggregata/assets/158275971/a109f44c-72b9-4f9d-ac5e-6bd74b3c2d72)

Once the upload is complete, you can view the relevant files in their respective folder.

## Configure HuggingFace Account Token
Certain models/datasets on HuggingFace require authorization or login credentials to download, while others may require specific permissions. To download these models/datasets, you must first configure your HuggingFace account token. Without doing so, you will encounter the same error message as shown below when attempting to use the **Import HuggingFace Project** feature.

![image](https://github.com/Aggregata-xyz/aggregata/assets/158275971/b319e7de-27b3-4d85-8907-03b0ae817f00)

After logging into HuggingFace, click on your avatar in the upper right corner and select Settings.
You can create a new token by following the steps: **Access Tokens -> New token**.

Enter the Token Name and select Role. The Name refers to the purpose of the Token, while the Role determines the Token permissions (the default one with read permissions can be enough). Click Generate a token to complete the creation process.

![image](https://github.com/Aggregata-xyz/aggregata/assets/158275971/a4131a7a-fa5f-472c-ba4e-f2c9acfafc66)

After generating the token, click the Copy icon on the page to copy it.

![image](https://github.com/Aggregata-xyz/aggregata/assets/158275971/57ff9ace-407b-4cc4-8fc7-1fb0fc13f6b5)

In **Aggregata**, click Settings located at the bottom left corner. Once you are on the Settings page, click the Settings button next to **HuggingFace Token**, and paste the copied Token to complete the step.

After configuring the HuggingFace Token, you can load the models and datasets that require authentication.

## Note:
- Some models/datasets may require additional disk space. Please pay attention to the capacity of the disk.
- Some models/datasets need additional permissions (e.g. Llama2), please apply for relevant permissions on the HuggingFace website before downloading.


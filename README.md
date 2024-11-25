## How to Use NiceHash Docker Container

This document explains how to set up and use the NiceHash mining container.

### How to Use

1. **Get Your NiceHash Mining Address:**
   First, create an account or log in to your existing account on the NiceHash website. Once logged in, navigate to the "Mining" tab, click on "Mining Address," and copy the displayed address.

2. **Configure the Docker Compose File:**
   In the provided Docker Compose file, replace `YOUR_MINING_ADDRESS` with the NiceHash mining address you just obtained. You can also set `MINING_WORKER_NAME` to any name you prefer (e.g., rig-rtx).

3. **Start the Container:**
   In the directory where the Docker Compose file is saved, run the following command to start the container:

   ```bash
   docker-compose up -d
   ```

This will start NiceHash mining in the background.

### How to Get Your NiceHash Mining Address

1. **Log in to Your NiceHash Account:**
   Go to the [NiceHash website](https://www.nicehash.com/) and create an account or log in to your existing account.

2. **Navigate to the Mining Tab:**
   After logging in, click on the "Mining" tab at the top of the dashboard.

3. **View Mining Address:**
   Click on the "Mining Address" button located in the top left corner of the "Mining" tab. Your mining address will be displayed. Copy this address and use it to configure the Docker Compose file.

### Important Notes

* This setup assumes an environment with an NVIDIA GPU.
* Docker and Docker Compose must be installed on your system.
* You can change `MINING_WORKER_NAME` to identify and manage multiple rigs.

We hope this document helps you set up and use the NiceHash mining container.

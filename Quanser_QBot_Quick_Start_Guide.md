# Quanser QBot Platform -- Quick Start Guide

## Step 1 -- Open Project in Visual Studio Code

1.  Launch **Visual Studio Code**.

2.  Navigate to the following folder path:

        Quanser/2_qucik_start_guides/qbot_platform/python

3.  Open the folder inside VS Code.

## Step 2 -- Run the Observer Script

Run the following script on your **host machine**:

    observer.py

## Step 3 -- Configure IP Address in `quick_start_qbot_platform.py`

1.  Open the file `quick_start_qbot_platform.py`.

2.  Go to **line 1697** and set the **ipHost address** to the **IP
    address of the host machine**.

3.  To find your IP address, run:

        ipconfig

    on your host machine.

## Step 4 -- Transfer File to QBot

1.  Use **WinSCP** to log in to the QBot using its **IP address**.
2.  Transfer the updated `quick_start_qbot_platform.py` file to the
    QBot.

## Step 5 -- Connect Using PuTTY

1.  Launch **PuTTY**.

2.  Connect to the QBot using its **IP address**.

3.  Navigate to the correct directory:

        cd Documents/Quanser/2_qucik_start_guides

## Step 6 -- Run the QBot Program

Execute the following command:

    sudo PYTHONPATH=$PYTHONPATH python3 quick_start_qbot_platform.py

-   The QBot's **LED light** should turn on.
-   Press the **top left button** on the joystick to drive the robot
    around.
-   Ensure the joystick is connected and set to the **"x"** position.

## Step 7 -- Adjust Simulation Time

To increase simulation time: 1. Search for `simulationTime` in
`quick_start_qbot_platform.py`. 2. Replace its value with your desired
duration. 3. Re-copy the modified file to the QBot.

> ⚠️ **Note:** The `observer.py` script must be running on the **host
> machine** for proper communication.

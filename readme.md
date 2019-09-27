This iOS MobileConfig will append the APN settings to allow dual SIM/eSIM function correctly with ATT Hotspot plans.


STEPS
  1) Go to settings > cellular > Cell Data and select the ATT Hotspot SIM and DISABLE "Allow Cellular Data Switching"
  2) Open the GitHub Repo FROM SAFARI and open the "attbroadband.mobileconfig" file.
  3) Click RAW to download the mobileconfig file and stage it for install.
  4) Navigate to Settings > General > Profiles & Device Management and install the Downloaded profile
  5) Verify ATT connectivity by checking your IP/Hostname (ie: http://ipchicken.com)
  6) Go back to settings > cellular > Cell Data & select your other SIM to verify data still works on that line. Once confirmed renable your        Data SIM and renable "Allow Cellular Data Switching"
  
NOTE: This has been tested on two devices with the other carrier being Verizon. T-Mobile users don't appear to have an issue with manually setting APNs

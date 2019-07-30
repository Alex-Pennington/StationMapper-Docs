============
Configuration
============

Configuration of settings is done through the menu Configure->Settings function.

.. image:: ../images/Settings.png
   :width: 404
   
Select NCS Application
--------
   - Choose either 'ACP Deluxe NCS' or 'StationManager v2 NCSPro'
   - Changing this setting forces StationMapper to restart.
   
Select ACP Deluxe Folder
--------
   - Enter the root folder for ACPDeluxe or click '...' to select one from a dialog window.
   - The default value is "C:/MSC/ACP Deluxe/"
   
Select Station Manager V2 Folder
--------
   - Enter the PENDING_OUT folder for SMv2 or click '...' to select one from a dialog window.
   - the default value is "C:/MSC/StationManagerV2/PENGING_OUT"
   
Settings
--------
   - Preserve Aspect Ratio
      - Selects weather the map is forced to preserve the aspect ratio when the window is resized.
      - May be removed in future versions and set to on permanantly.
      - For users with small screens or many windows open at once.
   - Calculator
      - Selects if calculator is displayed on map window.
      - Changing this setting forces StationMapper to restart.
   - Font Button
      - Displays font selection window.
      - Size set here has no bearing on map display.
   - Relay Lines
      - Select is lines are drawn beteewn station that is relayed to its relay station.
   - Station Status
      - Closed stations are displayed in red and crossed out.
      - Other funstions will be added. (after v0.316)
   - Grey Line
      - Displays the solar terminator on the map.
      - Currently a single line moving across the screen. (v0.316)
      - Will provide more options for this feature at a later time.

Weather
--------
   This feature is a limited resource, by signing up for your own AerisWeather.com developer account you can ease the burden on the developer of StationMapper (Please do this if you use this feature).  The account is free but requires renewal every two months.
   - Weather Checkbox
      - Displays weather radar overlay on map.
   - Signup for IDs
      - Opens URL to signup for API access tokens.
   - AccessID
      - Provided by AerisWeather.com developer account.
   - SecretID
      - Provided by AerisWeather.com developer account.
   
Import
--------
   - Import address.csv
      - Selects address.csv file to import.  On slower computer a progress dialog may display while the import is preformed.
   - Advanced
      - Starts the 'Advanced Database Tool'
      - Use this tool to import a user created CSV file with City, ST data.  Preforms an online lokup of City,St data and merges the result into the StationManager "Working_DB"

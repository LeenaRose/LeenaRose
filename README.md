- 👋 Hi, I’m @LeenaRose
- 👀 I’m interested in Data Governance, all things network and data related,finding my neiche and creating my own income or business. 
- 🌱 I’m currently learning Azure Arc and SAP and highly interested in geofencing, BTC and Airdropping, investing and AI. 
- 💞️ I’m looking to collaborate on anything! A business partner? A mentor? 
- 📫 How to reach me ... my email leeah@babydudemedia.com!

<!--- The only way to reach your goals is to be willing to constantly adapt. 
LeenaRose/LeenaRose is a ✨ special ✨ repository because its `README.md` (this file)
You can click the Preview link to take a look at your changes.
--->
    <script>
      let tokenClient;
      let accessToken = null;
      let pickerInited = false;
      let gisInited = false;

      // Use the API Loader script to load google.picker
      function onApiLoad() {
        gapi.load('picker', onPickerApiLoad);
      }

      function onPickerApiLoad() {
        pickerInited = true;
      }

      function gisLoaded() {
        // TODO(developer): Replace with your client ID and required scopes.
        tokenClient = google.accounts.oauth2.initTokenClient({
          client_id: 'CLIENT_ID',
          scope: 'SCOPES',
          callback: '', // defined later
        });
        gisInited = true;
    }
    </script>
    <!-- Load the Google API Loader script. -->
    <script async defer src="https://apis.google.com/js/api.js" onload="onApiLoad()"></script>
    <script async defer src="https://accounts.google.com/gsi/client" onload="gisLoaded()"></script>
    
# Codeigniter-Pitisan
Codeigniter Command Line Tool, like Laravel Artisan, it can use command to create Controller Model View in quickly.

# Install
  Step1. Open terminal or Download this zip.
  Step2. Move application/controllers/Pitisan.php in your project application/controllers.
  Step3. Open terminal and change directory to your project directory.
  
# Usage
  $php index.php pitisan # Watch default helper
  $ptp index.php pitisan controller # Watch controller help er
  $php index.php pitisan controller User # Create User.php controller file in controllers folder.
  $php index.php pitisan controller admin.User # Create User.php controller file in controllers/admin folder.
  etc. (refer the helper)
  
# Best Practice ( Create alias to your ~/.bash_profile)
  alias pitisan="php index.php pitisan"

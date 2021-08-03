# uwa-bootcamp-final-project
/** flag1  **/
michael@target1:/var/www/html$ grep -rie flag[1-9] *
service.html:                   <!-- flag1{b9bbcb33e11b80be759c4e844862482d} -->
wordpress/wp-includes/ID3/module.audio.ac3.php:                 $thisfile_ac3_raw_bsi['compre_flag2'] = (bool) $this->readHeaderBSI(1);
wordpress/wp-includes/ID3/module.audio.ac3.php:                 if ($thisfile_ac3_raw_bsi['compre_flag2']) {
wordpress/wp-includes/ID3/module.audio.ac3.php:                 $thisfile_ac3_raw_bsi['langcode_flag2'] = (bool) $this->readHeaderBSI(1);
wordpress/wp-includes/ID3/module.audio.ac3.php:                 if ($thisfile_ac3_raw_bsi['langcode_flag2']) {
wordpress/wp-includes/js/wp-emoji-loader.js:                    flag, flag2, emoji41, emoji42;
wordpress/wp-includes/js/wp-emoji-loader.js:                            flag2 = canvas.toDataURL();
wordpress/wp-includes/js/wp-emoji-loader.js:                            if ( flag === flag2 ) {
wordpress/wp-includes/js/wp-emoji-loader.js:                            flag2 = canvas.toDataURL();
wordpress/wp-includes/js/wp-emoji-loader.js:                            return flag !== flag2;
michael@target1:/var/www/html$ 


/** Sets up WordPress vars and included files. */
require_once(ABSPATH . 'wp-settings.php');
michael@target1:/var/www/html/wordpress$ clear
michael@target1:/var/www/html/wordpress$ cd ..
michael@target1:/var/www/html$ cd ..
michael@target1:/var/www$ ll
-bash: ll: command not found
michael@target1:/var/www$ ls
flag2.txt  html
michael@target1:/var/www$ 
michael@target1:/var/www$ cat flag2.txt 
flag2{fc3fd58dcdad9ab23faca6e9a36e581c}
michael@target1:/var/www$ 


Link to Google Drive
https://drive.google.com/drive/folders/1S1j9FdTZ6xXmU5GwXbuY8FzfTz_lmHrd?usp=sharing


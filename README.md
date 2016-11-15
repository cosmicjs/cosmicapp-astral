#Astral
###PHP Single Page Site
#####[View a demo here](http://astral.cosmicapp.co/)
[Sign up for Cosmic JS](https://cosmicjs.com/) to start managing content for your websites and applications faster and easier.
####Get Started
In ```config.php``` set your bucket slug:
```
$config = new stdClass();
$config->bucket_slug = "astral"; // bucket slug
$config->read_key = ""; // leave empty if not required
$config->write_key = ""; // leave empty if not required
```

Set up your local server by running [PHP's built-in web server](http://php.net/manual/en/features.commandline.webserver.php).  Run the following commands in your terminal:

```
cd astral
php -S localhost:8000
```

Go to [http://localhost:8000](http://localhost:8000) in your browser of choice.

###Server XMLRPC

**1. Panggil library**

```php
$this->load->library('xmlrpc');
$this->load->library('xmlrpcs');
```

**2. Setting mapping function**

```php
$config['function']['Greetings'];
```

**3. Initialisasi `$config`**

**4. Eksekusi server _(menunggu request dari client)_.**

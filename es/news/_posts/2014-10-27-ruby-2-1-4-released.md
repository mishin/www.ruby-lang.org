---
layout: news_post
title: "Liberada la versión de Ruby 2.1.4"
author: "nagachika"
translator: "David Padilla"
date: 2014-10-27 12:00:00 +0000
lang: es
---

La versión de Ruby 2.1.4 ha sido liberada.

Esta versión incluye correcciones de seguridad de las siguientes vulnerabilidades:

* [CVE-2014-8080: Negación de Servicio (DoS) por Expansión de XML](https://www.ruby-lang.org/es/news/2014/10/27/rexml-dos-cve-2014-8080/)
* [Cambio en las configuraciones por defecto de ext/openssl](https://www.ruby-lang.org/es/news/2014/10/27/changing-default-settings-of-ext-openssl/)

También incluye algunas otras correcciones de errores.

Para más detalles puedes ver los [tickets](https://bugs.ruby-lang.org/projects/ruby-21/issues?set_filter=1&amp;status_id=5)
y el [ChangeLog](http://svn.ruby-lang.org/repos/ruby/tags/v2_1_4/ChangeLog).

**Actualización:** Fue corregida una regresión incluida en 2.1.3:

{% highlight irb %}
>> { key: if true then 0 else 1 end }
SyntaxError: (irb):1: syntax error, unexpected modifier_if
{ key: if true then 0 else 1 end }
         ^
{% endhighlight %}

## Descarga

* [http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.4.tar.bz2](http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.4.tar.bz2)

      SIZE:   11992171 bytes
      MD5:    f4136e781d261e3cc20748005e1740b7
      SHA256: f37f11a8c75ab9215bb9f61246ef98e0e57e1409f0872e5cf59033edcf5b8d2a
      SHA512: 68db1567751166c5e7d24b6e5015124b8a15568c50556e1f429486395352fa56c4a195a74820ab135697924149d014b445b345a1b9755678aaf824fba79c606b

* [http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.4.tar.gz](http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.4.tar.gz)

      SIZE:   15127418 bytes
      MD5:    89b2f4a197621346f6724a3c35535b19
      SHA256: bf9952cdeb3a0c6a5a27745c9b4c0e5e264e92b669b2b08efb363f5156549204
      SHA512: 7a6c70ec60db9866d5988e53c75e5c7e7288d68d87ba74ad317a0f74be79b387d05f665d9273d24dc64edc011d396b6396d2c7b1de6fd6a03569103e5acdcc36

* [http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.4.tar.xz](http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.4.tar.xz)

      SIZE:   9392500 bytes
      MD5:    99aa2b01240d91edaecc2fc9d8254e44
      SHA256: e1cc5cbbcaa8644e282f04763d96057ddd6f443338a5019200e8726273e84fcf
      SHA512: b0fbecca0ffec8f6a3c5d27f62087628b8a79874b7bdbfd8ce39cfc5b6f5cb4da2f8a3e6031abae9c59273cf629f41cf5987e2a5f4c083b0f3a3b02eeb5d7dca

* [http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.4.zip](http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.4.zip)

      SIZE:   16656312 bytes
      MD5:    71c7afca08734f0105a06d2feea11422
      SHA256: bdb26a725e1fd7982f12d5390209064687def61c330b92597322e3898131391e
      SHA512: 7fd8d13810a4336dc498a6eb05e140825d52eca0317d0848152688060b95ce4c79ab6a10cf14ab2499ae559fb4676d86538eacd94fb262c16795067fb4f47614


## Comentarios de la entrega

Agradecemos a todos los contribuidores, programadores y usuarios que nos
reportaron los problemas y nos ayudaron a que se lograra esta versión.
Gracias por sus contribuciones.

## Historia

* Actualización 2014-10-27 21:00:00 (UTC)
* Publicado Originalmente 2014-10-27 12:00:00 (UTC)

## Services / OS
What has unicode or emoji support?
- Registrars/Domains: Whitelist blocked ❌ 😢😢😢 <!-- .element: class="fragment" data-fragment-index="0" -->
    - ...EXCEPT  .ws 🇼🇸 ✔<!-- .element: class="fragment" data-fragment-index="1" -->
- DNS: IDN  ✔ <!-- .element: class="fragment" data-fragment-index="2" -->
- Webservers: IDN ✔ <!-- .element: class="fragment" data-fragment-index="3" -->
- Browsers: IDN  ✔ <!-- .element: class="fragment" data-fragment-index="4" -->
- Mail: Postfix (3.0+) ✔ <!-- .element: class="fragment" data-fragment-index="5" -->

note:
    Unicode is needed for emoji
    Registrars block most unicode code points, whitelisting only specific points, becasue of security issues
    Webservers only need to understand ascii
    unicode/utf-8 and thus emoji is allowed in more and more places

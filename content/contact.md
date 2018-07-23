+++
date = "2017-03-18T10:59:56+01:00"
title = "Contato"
draft = false

+++

{{% summary %}}
Entre em contato conosco.
{{% /summary %}}

<div id="formspree" class='formspree'>
    <form action="https://formspree.io/diogo2fex@gmail.com" method="POST">
    <input type="text" name="_gotcha" style="display:none" />
    <input type="hidden" name="subject" value="comment to: {{ .Title }}">
    <input type="email" name="email" placeholder="Seu email" required>
    <textarea name="message" placeholder="Sua mensagem" rows=5 required></textarea>
    <button type="submit">Enviar</button><br><br>
</form>

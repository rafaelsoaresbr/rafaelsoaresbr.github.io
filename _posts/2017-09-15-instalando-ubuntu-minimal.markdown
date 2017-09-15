---
layout: post
title:  "Instalando o Ubuntu Xenial usando o Instalador via Rede"
date:   2017-09-15 11:12:34 -0400
categories: ubuntu
comments: true
---

Olá, neste tutorial vamos mostrar como instalar o Ubuntu 16.04 LTS (Xenial Xerus) usando o Instalador via Rede.

1 - O primeiro passo é baixar a iso do Instalador via Rede, disponível em:

http://cdimage.ubuntu.com/netboot/16.04/

2 - Após o download, no Terminal, execute o seguinte comando como administrador:

`# cp debian.iso /dev/sdX && sync`

Onde `sdX` é o dispositivo correspondente ao seu pendrive.

3 - Inicie o computador com o pendrive conectado, pode ser necessário pressionar F8, F9, F10 ou F12, dependendo da placa-mãe do seu computador para alterar a ordem de boot, depois basta seguir as instruções do instalador:

![Screenshot 01]({{ site.url }}/assets/ubuntu/instalando/01.png)

![Screenshot 02]({{ site.url }}/assets/ubuntu/instalando/02.png)

![Screenshot 03]({{ site.url }}/assets/ubuntu/instalando/03.png)

![Screenshot 04]({{ site.url }}/assets/ubuntu/instalando/04.png)

![Screenshot 05]({{ site.url }}/assets/ubuntu/instalando/05.png)

![Screenshot 06]({{ site.url }}/assets/ubuntu/instalando/06.png)

![Screenshot 07]({{ site.url }}/assets/ubuntu/instalando/07.png)

![Screenshot 08]({{ site.url }}/assets/ubuntu/instalando/08.png)

![Screenshot 09]({{ site.url }}/assets/ubuntu/instalando/09.png)

![Screenshot 10]({{ site.url }}/assets/ubuntu/instalando/10.png)

![Screenshot 11]({{ site.url }}/assets/ubuntu/instalando/11.png)

![Screenshot 12]({{ site.url }}/assets/ubuntu/instalando/12.png)

![Screenshot 13]({{ site.url }}/assets/ubuntu/instalando/13.png)

![Screenshot 14]({{ site.url }}/assets/ubuntu/instalando/14.png)

![Screenshot 15]({{ site.url }}/assets/ubuntu/instalando/15.png)

![Screenshot 16]({{ site.url }}/assets/ubuntu/instalando/16.png)

![Screenshot 17]({{ site.url }}/assets/ubuntu/instalando/17.png)

![Screenshot 18]({{ site.url }}/assets/ubuntu/instalando/18.png)

![Screenshot 19]({{ site.url }}/assets/ubuntu/instalando/19.png)

![Screenshot 20]({{ site.url }}/assets/ubuntu/instalando/20.png)

![Screenshot 21]({{ site.url }}/assets/ubuntu/instalando/21.png)

![Screenshot 22]({{ site.url }}/assets/ubuntu/instalando/22.png)

![Screenshot 23]({{ site.url }}/assets/ubuntu/instalando/23.png)

![Screenshot 24]({{ site.url }}/assets/ubuntu/instalando/24.png)

![Screenshot 25]({{ site.url }}/assets/ubuntu/instalando/25.png)

Pronto! Fizemos a instalação do Ubuntu sem interface gráfica `(Command-line install)`, opcionalmente você pode instalar o Ubuntu com a interface gráfica Unity selecionando a opção `(Install)` no começo, ou pode selecionar a opção `(Advanced options -> Expert install)` para escolher qual interface gráfica instalar.

Se você deseja instalar em dual-boot ou customizar o particionamento do disco recomendo usar as opções `(Advanced options -> Expert install)` ou `(Advanced options -> Command-line expert install)`, nelas o assistente de instalação pode automaticamente separar as partições `/` e `/home`. Lembrando que todas as opções dão a opção de particionamento manual.

Até a próxima!

{% if page.comments %}

  <div id="disqus_thread"></div>
  <script>

  var disqus_config = function () {
      this.page.identifier = MaM2trtu;
    };

  (function() {
  var d = document, s = d.createElement('script');
  s.src = 'https://rafaelsoaresbr-github-io.disqus.com/embed.js';
  s.setAttribute('data-timestamp', +new Date());
  (d.head || d.body).appendChild(s);
  })();
  </script>
  <noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

  <script id="dsq-count-scr" src="//rafaelsoaresbr-github-io.disqus.com/count.js" async></script>

{% endif %}

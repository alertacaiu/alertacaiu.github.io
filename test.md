---
title: Alerta&#58; Caiu!
description: Incidentes na Internet do Brasil
permalink: /test/
---

Receba os **alertas** de atividade da lista Caiu sobre indisponibilidades na **Internet brasileira**

<input type="checkbox" onclick="toggleAutoRefresh(this);" id="reloadCB"> Auto Refresh
<script>
  var reloading;

function checkReloading() {
    if (window.location.hash=="#autoreload") {
        reloading=setTimeout("window.location.reload();", 5000);
        document.getElementById("reloadCB").checked=true;
    }
}

function toggleAutoRefresh(cb) {
    if (cb.checked) {
        window.location.replace("#autoreload");
        reloading=setTimeout("window.location.reload();", 5000);
    } else {
        window.location.replace("#");
        clearTimeout(reloading);
    }
}

window.onload=checkReloading;
</script>

### Última publicação

Retransmissão mais recente:

<a 
  class="twitter-timeline lazyload" 
  data-lang="pt" 
  data-link-color="#BE102E" 
  data-tweet-limit="1" 
  data-chrome="noheader nofooter noborders" 
  data-script="//platform.twitter.com/widgets.js" 
  target="_blank" 
  rel="nofollow noopener noreferrer" 
  href="https://twitter.com/AlertaCaiu?ref_src=twsrc%5Etfw">
    O carregamento falhou, clique para carregar.
  </a>

<p class="smaller">Por padrão, somente a primeira interação referente a cada incidente é retransmitida, portanto podem haver discussões ativas mesmo quando a última mensagem já tiver sido publicada há um certo tempo.</p>

### Receber notificações

Para ser notificado(a) sobre **novas atualizações** basta seguir a conta @AlertaCaiu no Twitter: 

<a 
class="twitter-follow-button lazyload" 
data-size="large" 
data-show-count="false" 
target="_blank" 
rel="noopener noreferrer" 
href="https://twitter.com/AlertaCaiu?ref_src=twsrc%5Etfw">
  https://twitter.com/alertacaiu
</a>

<p class="smaller">Caso você deseje ser avisado(a) todas as vezes em que uma nova publicação for criada, ative a opção de notificação nas configurações do Twitter.</p>

### Visualizar mensagens

Para visualizar o inteiro teor das mensagens, acesse o **arquivo da lista** pelo Pipermail:

- [https://eng.registro.br/pipermail/caiu/](https://eng.registro.br/pipermail/caiu/){:target="_blank" rel="noopener noreferrer"}

<p class="smaller">Por não possuir design responsivo, a navegação nos arquivos é melhor em computadores, no entanto é possível utilizá-la em celulares aplicando o zoom.</p>

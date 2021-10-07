<template>
  <div class="viajapass">
    <h1>{{ msg }}</h1>
    <p>
      Os melhores passeios do destino inclusos em um único pass,<br>
      saiba mais em
      <a href="https://projeto-website-viajapass.vercel.app/home.html#funcionamento" target="_blank" rel="noopener">como funciona</a>.
    </p>
    <h3>Descubra +</h3>
    <ul>
      <li><a href="https://projeto-website-viajapass.vercel.app/atracoes-fln.html" target="_blank" rel="noopener">Atrações inclusas em Florianópolis</a></li>
      <li><a href="https://projeto-website-viajapass.vercel.app/atracoes-bc.html" target="_blank" rel="noopener">Atrações inclusas em Balneário Camboriú</a></li>
      <li><a href="https://projeto-website-viajapass.vercel.app/comprar.html" target="_blank" rel="noopener">Adquira o seu</a></li>
    </ul>
    <h3>Links importantes</h3>
    <ul>
      <li><a href="https://projeto-website-viajapass.vercel.app/faq.html" target="_blank" rel="noopener">FAQ</a></li>
      <li><a href="https://projeto-website-viajapass.vercel.app/atendimento.html" target="_blank" rel="noopener">Falar com a gente</a></li>
    </ul>
    <h3>Siga-nos</h3>
    <ul>
      <li><a href="https://www.tripadvisor.com/viajapass" target="_blank" rel="noopener">Tripadvisor</a></li>
      <li><a href="https://www.instagram.com/viajapass/" target="_blank" rel="noopener">Instagram</a></li>
      <li><a href="https://www.facebook.com/viajapass" target="_blank" rel="noopener">Facebook</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'ViajaPass',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
  color: #FA4067;;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #003C52;
}

p {
  color: #003C52
}
</style>

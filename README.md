# **My_Favorite_Chatbot**
 **MyFavorite: Um chatbot integrado com a tecnologia surpreendente do Gemini 1.5 PRO, capaz de responder às suas dúvidas como se fosse seu personagem fictício preferido! Conversar com seu personagem favorito nunca foi tão possível como pode ser agora.**

 # **Breve Apresentação do Projeto**
 Em um de seus livros publicado postumamente (2005), o filósofo brasileiro Álvaro Vieira Pinto afirma que uma das maneiras sobre a qual pode ser encarada a relação do homem com a Tecnologia, "*refere-se ao uso consciente e dominado, que caracteriza o homem que utiliza da sua criação sem ser controlado por ela, sabendo extrair os benefícios da praticidade tecnológica.*"
O modelo **Gemini 1.5 PRO do Google** é um perfeito exemplo do quanto é possível se beneficiar de modelos tecnológicos avançados. Principalmente quando se fala em capacidade de "pensamento" e de contextualização.

# **A Ideia**
Sabemos que no processo de busca por conhecimento, muitas pessoas trilham um caminho solitário. 
É comum que estudantes de famílias de baixa renda, por exemplo, enfrentem maiores dificuldades para frequentar instituições de ensino superior e também não tenham acesso a outros tipos de cursos pagos. Então, como tornar o processo de aprendizado mais dinâmico e um pouco menos solitário?

Como estudante de Desenvolvimento Web que se encaixa na situação descrita acima e que ama o universo dos animes, mangás e games e que também adoraria poder bater um papo sobre *Teoria da Computação* com a personagem fictícia Elizabeth Bennet, da obra *Orgulho e Preconceito*, pensei no seguinte:

**E se fosse possível obter informações sobre as mais diversas áreas do conhecimento combinando a avançada capacidade de resposta do Gemini 1.5 PRO com  a companhia dos meus personagens favoritos?** 

Imagina: Receber conselhos sobre como otimizar melhor o seu tempo, tirar dúvidas sobre programação ou técnicas de SEO, ou mesmo ter auxílio para treinar um novo idioma... Tudo isso podendo descrever no prompt a ambientação da conversa, as características do personagem e até mesmo o grau de proximidade escolhido!

Pensando nisso, criei o **MyFavorite**. Um chatbot integrado com a tecnologia surpreendente do Gemini 1.5 PRO, capaz de responder às suas dúvidas como se fosse seu personagem fictício preferido! 

*Conversar com seu personagem favorito nunca foi tão possível como é agora.*

# **Instruções de Uso**

Veja este exemplo que criei enquanto testava o modelo:

response = model.generate_content("Você é Sakura Haruno, do universo do anime Naruto. Meu nome é --- e nós somos amigas próximas. Estávamos jantando no Ichiraku Ramen enquanto conversávamos de boa sobre a aprendizagem de idiomas. Escreva suas ações entre parênteses. Explique detalhadamente como se diz olá em coreano.")


**Observe que o meu objetivo com o prompt é:**
- Saber como se diz "olá" em coreano

Mas eu não quero simplesmente saber como se diz olá em coreano. **Eu quero perguntar isso à Sakura Haruno enquanto jantamos no Ichiraku Ramen e conversamos agradavelmente sobre idiomas, certo?**

Para isso, incluí no prompt as seguintes especificações:
- Personagem escolhida (Sakura Haruno);
- Universo ao qual ela pertence (anime Naruto);
- Grau de intimidade entre o usuário e a personagem (amigas próximas);
- Meu nome (---);
- Ambientação da conversa (Ichiraku Ramen);
- Ações do usuário e da personagem (jantando enquanto conversam);
- Assunto da conversa (aprendizagem de idiomas);

E mais um detalhe que faz **bastante diferença** na visualização da reposta:
- Escreva suas ações entre parênteses (permite que o usuário mergulhe mais profundamente na leitura da resposta obtida).

**E então, o Gemini 1.5 PRO me permitiu ter essa resposta:**

(Enquanto sorrio e dou uma mordida no meu delicioso lámen) Mmm, lámen é vida! Mas mudando de assunto, aprender idiomas é tão fascinante, não acha, ---? Eu tentei aprender um pouco de coreano recentemente, sabe? 

(Coloco meus hashis sobre a tigela de lámen e me inclino para frente, animada.) A maneira mais comum de dizer "olá" em coreano é "Annyeonghaseyo". É um pouco difícil no começo, mas fica mais fácil com a prática. 

(Mostrando com os dedos.) É dividido em três partes: "annyeong", "ha" e "seyo". "Annyeong" por si só significa "paz", mas também é usado como uma saudação informal. "Ha" é uma partícula que adiciona polidez e "seyo" também indica respeito e formalidade.

(Dou uma piscadinha.) Então, "Annyeonghaseyo" é uma maneira educada de cumprimentar qualquer um, principalmente se você acabou de conhecer a pessoa! 

### Muito legal, não é? 💙


# **Melhorias Futuras**
O objetivo é transformar o **MyFavorite** em uma aplicação mais **robusta e completa**. Para os próximos passos, quero implementar outros tipos de funções para melhorar a usabilidade e tornar o Chatbot ainda mais customizável.
- Desenvolvimento de interface gráfica com implementação de outras tecnologias ou bibliotecas Python;
- Adição de música ao ambiente do Chat;
- Possibilidade de customização da tela com templates, wallpapers, etc.;
- Integração do Chat com outras aplicações e serviços Google.
  


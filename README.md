# 📊 Relatório de Uso do Azure Language Studio

## 🧠 Importância do Azure Language Studio para Empresas

O Azure Language Studio oferece uma plataforma poderosa baseada em inteligência artificial para análise de linguagem natural, permitindo que empresas:

- **Melhorem o atendimento ao cliente**, analisando sentimentos e intenções em conversas.
- **Agilizem processos internos**, automatizando tarefas como classificação de texto e extração de informações.
- **Tomem decisões estratégicas mais inteligentes**, com base em dados linguísticos extraídos de documentos, e-mails e redes sociais.
- **Criem produtos mais personalizados**, entendendo melhor o comportamento e necessidades dos usuários por meio da linguagem.

## ⚙️ Processo Realizado no Azure

Durante meus testes no Azure Language Studio, realizei os seguintes passos:

### 1. Criação do Recurso de Linguagem

- Acesse o [Azure Portal](https://portal.azure.com).
- Criei um recurso de Linguagem (Language Resource), configurando:
  - Local da instância  
  - Grupo de recursos  
  - Plano de tarifa  
  - Região de operação  
- Após a criação, obtive a **chave de acesso** e o **endpoint** para uso em aplicações externas.

### 2. Testes com o Language Studio

- Acesse o [Azure Language Studio](https://language.azure.com).
- Utilizei três tipos de texto em **inglês** para testar a funcionalidade de **detecção de sentimentos**:

#### Texto positivo
> "I was genuinely impressed by the customer service. The team responded quickly, solved my issue efficiently, and made me feel valued. The product arrived ahead of schedule and exceeded my expectations. I would definitely recommend this company."

✅ Classificado como **positivo**, destacando rapidez no atendimento e satisfação com o produto.

#### Texto negativo
> "I'm extremely disappointed with the service. The support team was slow, unhelpful, and gave me conflicting information. The product arrived damaged, and I never received a response to my complaint. I would not recommend this company."

❌ Detectado como **negativo**, com ênfase em problemas com suporte e produto danificado.

#### Texto misto
> "The customer support team was friendly and tried their best to help me, which I really appreciated. However, the process took too long, and I had to follow up multiple times to get a resolution. The product itself works fine now, but the initial experience was frustrating."

⚖️ Avaliado como **misto**, reconhecendo aspectos positivos no atendimento e negativos na demora na resolução.

- Também experimentei:
  - **Extração de entidades**: nomes de empresas, prazos e avaliações foram reconhecidos automaticamente.
  - **Classificação personalizada**: testei categorias como “satisfação do cliente” e “eficiência do suporte”.

## 📌 Conclusão

O Azure Language Studio se mostrou uma ferramenta valiosa para projetos que envolvem tratamento e análise de texto em escala. Sua interface acessível e recursos avançados tornam o uso da IA em linguagem natural uma realidade para empresas de diferentes portes e setores.

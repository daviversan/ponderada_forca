# Requisitos Funcionais e Não Funcionais para Jogo de Forca Online

## Requisitos Funcionais  

1. **Cadastro e Autenticação:**  
   - Permitir que os usuários criem contas com email e senha.  
   - Opção de login com redes sociais (Google, Facebook).  

2. **Modos de Jogo:**  
   - Modo single player com palavras aleatórias.  
   - Modo multiplayer para competir com outros jogadores.  
   - Níveis de dificuldade: fácil, médio e difícil.  

3. **Mecânica do Jogo:**  
   - Exibir as letras corretas quando adivinhadas.  
   - Contagem de tentativas erradas com representação visual (exemplo: desenho do boneco).  
   - Notificação ao jogador ao vencer ou perder uma rodada.  

4. **Pontuação:**  
   - Sistema de pontos baseado em acertos e tempo de resposta.  
   - Ranking público para jogadores com melhores pontuações.  

5. **Gerenciamento de Palavras:**  
   - Banco de dados com palavras variadas para diferentes categorias.  
   - Opção de seleção de categorias pelo jogador (exemplo: frutas, filmes, tecnologia).  


## Requisitos Não Funcionais  

1. **Desempenho:**  
   - O tempo de resposta para cada interação deve ser inferior a 1 segundo.  

2. **Escalabilidade:**  
   - Suporte a até 1000 usuários simultâneos.  

3. **Segurança:**  
   - Criptografia de senhas no banco de dados.  
   - Proteção contra ataques de força bruta e SQL Injection.  

4. **Compatibilidade:**  
   - Funcionar em navegadores modernos (Chrome, Firefox, Edge, Safari).  
   - Interface responsiva para desktop, tablet e dispositivos móveis.  

5. **Disponibilidade:**  
   - Disponibilidade mínima de 90,5% ao longo do mês.  
# Engenharia de Requisitos 

- RF
    1. Renovação Online: O sistema deve permitir que o aluno renove livros pela plataforma, mesmo fora do horário da biblioteca.
    2. Consulta de Acervo:  O sistema deve permitir ao usuário consultar a disponibilidade de livros em tempo real.
    3. Reserva de salas: O sistema deve permitir a reserva de salas de estudo pelo aplicativo ou web.
    4. Cálculo automático de multas: O sistema deve registrar empréstimos e devoluções automaticamente.
    5. Pagamento Digital: O sistema deve calcular automaticamente multas de atraso no ato da devolução.
    6. Lembretes: O sistema deve enviar alertas sobre prazos de devolução, reservas e multas.
    7. Cadastro Digital: O sistema deve permitir o cadastro e autenticação de alunos e funcionários.
    8. Empréstimos e devoluções: O sistema deve registrar empréstimos e devoluções automaticamente.
- RNF
    1. Disponibilidade: O sistema deve estar disponível 24/7, exceto durante manutenções agendadas.
    2. Desempenho:  Consultas ao acervo devem retornar resultados em até 2 segundos.
    3. Segurança: Todos os dados de usuário devem ser armazenados criptografados.
    4. Usabilidade: A plataforma deve ser responsiva e acessível em dispositivos móveis.
    5. Integridade: O sistema deve impedir alterações manuais no cálculo automático de multas.
    6. Escalabilidade: Deve suportar 500 acessos simultâneos sem degradação perceptível.
    7. Confiabilidade: As informações de empréstimos e devoluções devem possuir backup automático diário.
    
- RN
    1. Limite de Renovação: Um livro pode ser renovado apenas 2 vezes, desde que não haja reserva pendente.
    2. Multas: A multa diária por atraso é fixa (R$ X,XX por dia), aplicada automaticamente.
    3. Bloqueio de Empréstimos: Alunos com multa acima de R$ 20 não podem realizar novos empréstimos até quitarem o valor.
    4. Cancelamentos de Reservas de Sala:  Cancelamentos só podem ser feitos até 2 horas antes do horário agendado
    5. Reservas de Sala: A sala só pode ser reservada por períodos de 1h a 3h.
    6. Perda de Livro:  Livros perdidos só são quitados mediante pagamento do valor atualizado do livro.
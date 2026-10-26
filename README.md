# ERB · SAML

Painel de arbitragem da **South America MPS League**, operado pela European Referee Board:
árbitros, folha de pagamento, rankings, desempenho, súmulas e possível escala.

Site: https://daavisaotg.github.io/saml-manager/

Página única em HTML. Os dados ficam num banco Postgres próprio no Supabase, separado do
painel da ERB: leitura pública, escrita apenas para quem tem acesso.

## Diferenças em relação ao painel da ERB

- Banco de dados próprio, sem nenhum ponto em comum com o da ERB.
- Marcação de **Autodraw**, com as mesmas regras do W.O.: já contado no MAIN, 20 minutos
  no tempo médio e valor próprio.
- **Tier** escolhido numa lista: Tier 1, Tier 2, Tier 3 e Trial Ref.
- O desempenho completo (punições, Big Matches, histórico recente e o resto) pode ser
  editado direto no formulário do árbitro.
- Entrada por senha, com opção de continuar conectado por 30 dias.
- Times da SAML Elite e da SAML Challenger já cadastrados.

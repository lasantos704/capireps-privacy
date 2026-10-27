# Política de Privacidade — CapiReps

Última atualização: 27/10/2026

O CapiReps é um aplicativo de registro de treinos de musculação que funciona
100% no seu aparelho. Não há cadastro, login, servidores ou serviços de nuvem
operados por nós.

## Dados armazenados

Treinos, rotinas, exercícios, séries (carga, repetições, tempo, distância, RPE,
observações), observações do treino, check-in autorrelato de prontidão e dificuldade,
duração adaptada da sessão, perfis de equipamento (barra e estoque de anilhas),
metas semanais por músculo, recordes, XP,
níveis, ofensiva, conquistas, missões pessoais e seus recibos de conclusão, peso corporal, preferências (tema, sons, vibração,
unidade kg/lb e idioma da interface) e configurações. A seção Saúde é opcional e permite registrar altura, idade declarada
com data de referência, pesos, circunferências corporais, lado, origem, data/fuso
conhecidos e observações sobre a medição. Também permite digitar laudos externos de
bioimpedância: aparelho, método, frequência, idade/altura/parâmetro/peso usados no
exame, métricas de composição, água, energia e valores avançados, condições e
observações. A seção Saúde também permite manter um catálogo manual de alimentos e
receitas, registrar refeições com descrição, kcal, macros e porção, bebidas com volume,
categoria e descrição, e confirmar os registros de um dia. Não há catálogo online nem
importação automática de valores. O celular não mede composição corporal e o app não se
conecta a aparelhos. Não mede nem diagnostica condições de saúde. Tudo fica armazenado
localmente em SQLite
e armazenamento do app. A revisão de Saúde e o relatório em texto são gerados no
próprio aparelho a partir desses registros, sem envio automático; o relatório é um
arquivo temporário de compartilhamento. Não oferecemos criptografia própria do banco
nem bloqueio biométrico; proteja o acesso ao aparelho.

## Coleta e compartilhamento

Não coletamos, não transmitimos e não compartilhamos seus dados pessoais. O app
funciona sem internet. Não usamos analytics, rastreamento, publicidade ou SDKs
de terceiros que coletem dados.

## Backup e exportação

Você pode exportar um JSON completo e compartilhá-lo pelo sistema. O arquivo inclui
Saúde, observações de treino e de série, check-in do treino, duração adaptada,
perfis de equipamento, alternativas curadas, metas semanais por músculo, metas,
catálogo de alimentos, receitas, refeições, bebidas, confirmações do dia, missões
pessoais e seus
recibos de conclusão, mesmo com resumos ocultos, e não é criptografado: quem o receber
poderá ler seus dados. Confira o destino e se o arquivo foi salvo. Importar exige
revisão das contagens e confirmação: substitui todos os dados, inclusive Saúde.
Um backup antigo sem metas por músculo, observações de série, Saúde, metas, consumo,
catálogo, receitas, confirmações, missões ou perfis de equipamento apaga
os registros atuais dessas áreas.

O CapiReps não envia backups automaticamente. O sistema operacional pode copiar ou
transferir dados conforme o fabricante e suas configurações de backup/migração;
a operação offline não garante exclusão dessas cópias.

A cópia de importação no cache é removida depois da leitura, sem apagar o original.
Para não interromper o destinatário, cópias temporárias de exportação (backup, CSV,
planos e cards) e relatórios de Saúde são removidos na próxima exportação após mais de
24 horas. Uma falha ao compartilhar remove a cópia recém-criada.
O relatório de Saúde só é gerado e compartilhado por ação sua; o app não o envia a
servidores. Quem receber o texto poderá lê-lo e copiá-lo.

Além do backup, você pode exportar outros três arquivos, sempre por ação sua e pelo
seletor do sistema, que poderão ser lidos por quem os receber:

- **CSV do histórico**: uma linha por série, com datas, carga, repetições, tempo,
  distância, RPE e as observações que você escreveu. Contém **só dados de treino**;
  nenhum registro de Saúde entra no arquivo.
- **Arquivo de plano (JSON)**: estrutura de rotinas, blocos e programas com os
  exercícios e séries necessários. Não contém histórico, peso, medidas, exames,
  alimentação, metas de Saúde, conquistas nem XP. Importar um plano **cria cópias
  novas** do que você marcou e nunca substitui nem apaga o que já existe; escolher o
  arquivo não altera nada até você conferir a prévia e confirmar.
- **Card de sessão (imagem PNG)**: gerado no aparelho a partir de um treino
  finalizado, mostrando apenas os blocos que você ligou em Ajustes → Card de sessão
  (data, duração, volume, séries, XP, ofensiva, recordes, lista de exercícios, marca
  e, se você ligar essa opção, a observação do treino). Dados de Saúde nunca aparecem
  no card.

Ao apagar somente Saúde, são removidos backups e relatórios temporários; CSVs, planos
e cards são dados de treino e ficam preservados. Ao apagar todos os dados, todas essas
cópias temporárias são removidas.

## Notificações, lembretes e widget

Sons, vibração e notificações são locais, gerados no próprio aparelho. Nenhum servidor é usado.
Os lembretes de treino e de registro são opcionais, nascem desligados e só passam a existir depois
de você conceder a permissão do sistema. O texto do aviso usa só rótulos fixos: nenhum título de
rotina, observação, exercício ou valor de Saúde aparece na tela bloqueada. O widget da tela inicial
também é opcional e desligado por padrão; quando você liga, ele mostra o próximo passo do seu plano
(o dia e o título da rotina) dentro do aplicativo da tela inicial do aparelho. Nada disso é enviado
por nós, e desligar limpa o conteúdo do widget.

## Exclusão de dados

Em Saúde → Apagar Saúde, você remove perfil de Saúde, pesos (incluindo antigos),
medidas, exames de bioimpedância, metas, catálogo de alimentos, receitas, refeições,
bebidas, confirmações do dia e backups/relatórios temporários, preservando treinos,
XP, missões pessoais, perfis de equipamento e preferências. Também pode editar/apagar registros individualmente;
ao apagar um exame vinculado, escolhe se a pesagem associada também será removida.
Sem pesos, a força relativa fica sem referência. Ajustes → Apagar todos os dados
remove também os demais dados. Desinstalar remove os dados locais do app.

A exclusão local é lógica, não garantia de apagamento forense do armazenamento.
Cópias exportadas e backups do sistema não são revogados e devem ser geridos por
você. Não temos servidores com dados pessoais a excluir.

## Crianças

O app não é direcionado a crianças e não coleta dados de menores.

## Contato

contato.capistudios@gmail.com

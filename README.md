# e107 Portuguese Language Pack v2.4.0
## Ficheiros de Língua PORTUGUESA (Portugal)

* Revisão: 2.0
* Data lançamento: 2026-04-25
* Autor: Kanonimpresor - <kanonimpresor@gmail.com>


## DESCRIÇÃO

Este pack de arquivo contém os ficheiros (codificação utf-8) em Português de Portugal para a versão v2.4.0 do sistema de gestão de conteúdo e107. A tradução foi efetuada a partir dos originais em Inglês da mesma versão, e contém as seguinte pastas e arquivos:

> 🆕 **Novidade v2.4.0** — Os ficheiros de ajuda em `e107_docs/help/Portuguese/` foram reescritos para tirar partido do novo renderizador enriquecido do painel de administração (PR upstream [#5596](https://github.com/e107inc/e107/pull/5596)). Suportam agora marcadores como `H1>`, `P>`, `NOTE>`, `TIP>`, `WARN>`, `SHOT>` (capturas de ecrã), `STEP>` (passos numerados), `IMG>` e `CODE>`, mantendo retrocompatibilidade total com o formato legacy `Q>/A>`.

## ESTRUCTURA DA DIRECTORIA
```
├── e107_docs/
|   └── help
├── e107_languages/
│   └── Portuguese/
│       |  ├── Portuguese.xml
|       |  └── ()
│       └── admin/
|            | └── ()
│            └── help/
├── e107_plugins
├── e107_themes
└── e107_web
  ()
```

## INSTRUÇÕES 
Para poder usar esta tradução, deverá efectuar a [transferência](https://github.com/Kanonimpresor/Portuguese) de todos as pastas e ficheiros desde o botão verde [<> Code] --> Download ZIP. 
Manter intacta, após descarregar e descompactar no seu computador, toda a estrutura/directorias de e107 para poder carregar, via FTP ou Cpanel, o diretório do e107 no seu servidor.

## CONDIÇÕES DE UTILIZAÇÃO
Estes ficheiros são fornecidos tal como os encontrou no arquivo original de distribuição. Poderá actualizá-los e alterá-los como entender na sua instalação pessoal do e107.
O autor não se responsabilizará por quaisquer erros na base de dados ou ficheiros da sua instalação do e107 resultantes da má instalação / utilização destes ficheiros.

## SUGESTÕES
Apesar de todos os ficheiros terem sido testados exaustivamente numa instalação de e107, é bem possível não tenham sido detectados alguns erros - letras trocadas ou falta de tradução em alguma linha/expressão...
Se detectar algum erro e desejar alertar o autor para a correcção do mesmo, poderá enviar um mail para <kanonimpresor@gmail.com> com a seguinte informação:
- página onde detectou o erro;
- expressão/palavra errada;

## HISTÓRICO
v2.0 [2026-04-25] => Reescrita dos 21 ficheiros de `e107_docs/help/Portuguese/` com os novos marcadores enriquecidos (`H1>`, `P>`, `NOTE>`, `TIP>`, `WARN>`, `SHOT>`, `STEP>`, `IMG>`, `CODE>`) introduzidos pelo PR upstream [#5596](https://github.com/e107inc/e107/pull/5596). Compatível com e107 v2.4.0 e retrocompatível com instalações v2.3.x (fallback para parágrafos planos + BBCode quando o renderizador antigo não interpreta os marcadores).

v1.0 [2025-05-04] => Primeiro lançamento oficial da tradução PT-PT .utf-8 (v2.3.3).

## LICENÇA

e107 Portuguese Language Pack v2.4.0, lançado nos termos e condições da GNU [General Public License](http://www.gnu.org/licenses/gpl.txt)


[EOF]

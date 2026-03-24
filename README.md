# Git as Gaeilge

## Réamhrá

An teanga a úsáidtear go laethúil leis na horduithe éagsúla i `git` (nó `amadán`)
— is meascán mearaí Béarla agus Gaeilge atá ann i ndáiríre. Bím féin go minic
ag rá rudaí cosúil le _"An féidir leat an branch a phúlláil?"_ nó _"Tá mé
ag púsáil anois!"_, rud a chuireann náire an domhain orm.

Is é aidhm an doiciméid seo ná jargón glan Gaeilge a leagan amach ar féidir
linn é a úsáid san ionad oibre, ionas go seachnóimid cásanna ciotacha le
comhghleacaithe agus le beithígh araon.

## Moltaí

Thíos tá táblaí de bhriathra agus d'ainmfhocail a bhaineann le git,
an Béarlachas atá in úsáid faoi láthair, agus moltaí maidir le conas
is féidir linn feabhas a chur orainn féin.

| Briathar     | Béarlachas         | Moladh          |
|--------------|--------------------|-----------------|
| init         | initáil            | tosaigh         |
| add          | addeáil            | cuir leis       |
| pull         | púlláil            | tarraing        |
| push         | púsáil             | brúigh          |
| fetch        | feitseáil          | fáigh           |
| clone        | clónáil            | macasamhlaigh   |
| branch       | brainseáil         | craobhaigh      |
| commit       | commitáil          | tiomnaigh       |
| rebase       | rébasáil           | athbhunaigh     |
| diff         | diffeáil           | comparáidigh    |
| merge        | méirgeáil          | cumasc          |
| squash       | squaisáil          | fáisc           |
| stash        | staisáil           | folaigh         |
| tag          | tagáil             | clibeáil        |
| fork         | forkeáil           | gabhlaigh       |
| cherry-pick  | cherry-pickeáil    | pioc silíní     |
| checkout     | checkeáil amach    | seiceáil        |
| amend        | amendeáil          | leasaigh        |
| blame        | blaméil            | lochtaigh       |

| Ainmfhocal     | Béarlachas      | Moladh                    |
|----------------|-----------------|---------------------------|
| git            | git             | amadán                    |
| github         | github          | lár na n-amadán           |
| gitlab         | gitlab          | saotharlann na n-amadán   |
| repository     | repo            | stóras                    |
| branch         | branch          | craobh                    |
| commit         | commit          | tiomantas                 |
| pull request   | pull request    | iarratas tarraingthe      |
| merge request  | merge request   | iarratas cumaisc          |
| stash          | stash           | folachán                  |
| tag            | tag             | clib                      |
| fork           | fork            | gabhal                    |
| log            | log             | dialann                   |
| status         | status          | stádas                    |
| diff           | diff            | comparáid                 |
| origin         | origin          | bunús                     |
| master         | master          | máistir                   |
| main           | main            | príomh                    |

## Samplaí

    - An féidir leat an chraobh a tharraing a d'athbhunaigh mé díreach ansin, agus í a bhrú go lár na n-amadán?

    - Tá stóras nua tosaíthe agam — macasamhlaigh é agus tóg an chraobh forbartha.

    - Chraobhaigh mé ansin díreach agus thiomnaigh mé na hathruithe as an bhfolachán.

    - Cuir iarratas tarraingthe chugam nuair atá an cumasc déanta agat!

    - Piocaimis na silíní ón máistir-chraobh.

    - Úps, thug mé trom-bhrú ar an máistir-chraobh de thaisme.. D:

    - Fáisc do chuid tiomantas sula ndéanann tú cumasc.

    - Gabhlaigh i lár na n-amadán!

    - Is féidir leat sa dialann feiceáil cé a rinne an tiomantas fáiscthe deireanach a chumasc.

## Úsáid laethúil

Thíos tá roinnt orduithe don líne ordaithe chun timpeallacht Ghaeilge a chur
ar bun le haghaidh git. Níl síntí fada sna leasainmneacha mar gheall ar easpa
tacaíochta i git féin (smaoinigh ar an mbogearraí a fheabhsú agus iarratas
tarraingthe a sheoladh!). Athróidh na horduithe seo do `~/.gitconfig` agus
beidh siad i bhfeidhm go huilíoch.

Is féidir iad ar fad a chur ar bun in aon iarracht amháin le `bash as-gaeilge.sh`,
nó ceann ar cheann:

    git config --global alias.tosaigh init
    git config --global alias.cuirleis add
    git config --global alias.tarraing pull
    git config --global alias.bruigh push
    git config --global alias.faigh fetch
    git config --global alias.macasamhlaigh clone
    git config --global alias.craobh branch
    git config --global alias.craobhaigh branch
    git config --global alias.tiomnaigh commit
    git config --global alias.athbhunaigh rebase
    git config --global alias.comparaidigh diff
    git config --global alias.cumasc merge
    git config --global alias.faisc 'merge --squash'
    git config --global alias.folaigh stash
    git config --global alias.clibeail tag
    git config --global alias.clib tag
    git config --global alias.piocsilinii cherry-pick
    git config --global alias.seiceail checkout
    git config --global alias.leasaigh 'commit --amend'
    git config --global alias.lochtaigh blame
    git config --global alias.dialann log
    git config --global alias.stadas status
    git config --global alias.trombruigh 'push --force'

Chun `amadán` a úsáid in áit `git`, cuir an méid seo le do `~/.bashrc` nó
`~/.zshrc`:

    alias amadán=git

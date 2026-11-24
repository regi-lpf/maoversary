# Maoversary

Aplicação web estática em arquivo único que exibe uma citação de *Citações do Presidente Mao Zedong* (o *Livro Vermelho*) correspondente ao dia e mês do seu aniversário.

## Funcionalidades

- **Consulta por data (dia/mês):** seleção direta de dia e mês, iniciando automaticamente na data atual.
- **Pareamento por data histórica:** cada citação é vinculada à data informada na sua referência bibliográfica original (427 citações distribuídas pelos 33 capítulos).
- **Preenchimento e listas por data:** citações sem dia exato (apenas mês/ano ou ano) preenchem os dias vazios do seu mês correspondente; excedentes de datas repetidas completam o calendário e datas com múltiplas ocorrências mantêm uma lista ordenada da mais antiga para a mais recente, exibindo uma por vez com opção de alternar.
- **Cópia em texto ou imagem:** botões para copiar a citação formatada em texto ou gerar e copiar o card em PNG (com fallback automático para download).
- **Visual temático:** interface inspirada nas cartilhas e panfletos da Revolução Chinesa, responsiva para desktop e celular.

## Como usar

1. Acesse o [*deploy*](https://regi-lpf.github.io), ou baixe e abra o arquivo `livro_vermelho_aniversario.html` diretamente no navegador (não requer servidor, instalação nem conexão com a internet).
2. Escolha o **Dia** e o **Mês** nos seletores ou clique em **Aleatória** para explorar outras datas.
3. Use **Copiar Card (PNG)** ou **Copiar Citação** para compartilhar o resultado.

## Fonte dos dados

- Texto base: [*Citações do Presidente Mao Zedong*](https://www.marxists.org/portugues/mao/1966/citas/index.htm) -- Edição Digital em Português do Arquivo Marxista na Internet (2024), seguindo a tradução de 1972 das Edições em Línguas Estrangeiras (Pequim).

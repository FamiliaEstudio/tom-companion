# Integração com a linguagem Tom

Este repositório controla as alterações próprias de **tom-companion**. A linguagem e o ambiente
de compilação ficam no repositório [LinguagemTom](https://github.com/FamiliaEstudio/LinguagemTom),
atualmente privado. O aplicativo ainda depende dos caminhos relativos daquele projeto;
por isso o clone isolado não compila sozinho.

Para desenvolver e testar, mantenha um clone de LinguagemTom e copie os arquivos deste
repositório para `aplicativos/tom-companion/` dentro dele, preservando a estrutura.
- `integracao-vscode/` corresponde a `tom-lang/companion/` na árvore de LinguagemTom.

Faça mudanças na linguagem em LinguagemTom e mudanças no aplicativo aqui. Integre e
teste as duas árvores juntas antes de publicar uma versão. Não edite as duas cópias
do aplicativo em paralelo; confira o diff antes de sincronizar.

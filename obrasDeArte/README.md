Serialização das Classes de Modelo 
Todas as classes de modelo (ObraDeArte, Pintura, Escultura) implementam a interface Serializable. Isso permite que os objetos dessas classes sejam convertidos em bytes e salvos em arquivos, possibilitando a persistência dos dados.

Métodos para Salvar e Carregar Dados no Museu: 
A classe Museu foi atualizada com métodos para salvar e carregar dados usando ObjectOutputStream e ObjectInputStream. Esses métodos permitem que os objetos de obras de arte sejam gravados e lidos de um arquivo.

Integração com o Sistema
No início do programa, os dados são carregados do arquivo. Ao sair do sistema, os dados são salvos automaticamente.
# Atividade prática - Construção de Aplicativos

A atividade para o módulo de **Construção de Aplicativos** deve ser entregue até o dia 22/12/2017 consiste em 2 etapas:

## 1ª etapa - Criar um archetype Maven (70% da nota)

Este archetype deve conter as seguintes dependências declaradas ao ser utilizado:

    <dependency>
        <groupId>com.google.guava</groupId>
        <artifactId>guava</artifactId>
        <version>19.0</version>
    </dependency>

    <dependency>
        <groupId>junit</groupId>
        <artifactId>junit</artifactId>
        <version>4.12</version>
        <scope>test</scope>
    </dependency>

    <dependency>
      <groupId>org.apache.logging.log4j</groupId>
      <artifactId>log4j-api</artifactId>
      <version>2.8.2</version>
    </dependency>
    <dependency>
      <groupId>org.apache.logging.log4j</groupId>
      <artifactId>log4j-core</artifactId>
      <version>2.8.2</version>
    </dependency>

Além disso, o archetype deve conter 2 arquivos de propriedades no diretório `src/main/resources`:

- application.properties
- connection.properties

Este archetype deve estar em um repositório **Git** na organization da disciplina com o nome `<nome_do_aluno>-archetype` onde <nome_do_aluno> deve ser substituído pelo seu nome. Neste repositório deve conter um arquivo `README.md` com as instruções para baixar e instalar o archetype na máquina de quem for utilizar.

## 2ª etapa - Criar um artefato baseado neste arquetipo e distribuir via Bintray (30% da nota)

Após concluir a primeira etapa, inicie um novo projeto baseado no seu artifact e faça `deploy` do mesmo no **Bintray**. Para fazer esse deploy, siga esse guia: https://blog.bintray.com/2015/09/17/publishing-your-maven-project-to-bintray/

Este archetype deve estar em um repositório **Git** na organization da disciplina com o nome `<nome_do_aluno>-artifact` onde <nome_do_aluno> deve ser substituído pelo seu nome. Neste repositório deve conter um arquivo `README.md` que indica o endereço do repositório Maven no Bintray.

Qualquer dúvida, respondam o tópico no Classroom.
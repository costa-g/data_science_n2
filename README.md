# Projeto de Análise Eleitoral

Este projeto tem como objetivo analisar dados eleitorais e gerar visualizações através de um dashboard interativo utilizando Streamlit.

IMPORTANTE: Para executar o analise_eleitoral.py, é necessário ter uma hierarquia de pastas e arquivos como no exemplo abaixo:

data/candidatos/{files}

data/candidatos_bens/{files}

data/candidatos_info_complementar/{files}

data/candidatos_propostas_governo/SC/{files}

data/candidatos_redes_sociais/{files}

data/coligacoes/{files}

data/motivo_cassacao/{files}

data/vagas/{files}

Devido ao tamanho dos arquivos, não foi possível fazer o upload da pasta no git.

## Pré-requisitos

Certifique-se de ter o Python 3.6 ou superior instalado em seu sistema. Você pode verificar a versão instalada com o seguinte comando:

```bash
python --version
```

## Instruções de Execução

Siga os passos abaixo para configurar e executar o projeto.

### 1. Criar um Ambiente Virtual

Primeiro, crie um ambiente virtual para isolar as dependências do projeto:

```bash
python -m venv venv
```

### 2. Ativar o Ambiente Virtual

Ative o ambiente virtual:

- No Windows:

  ```bash
  venv\Scripts\activate
  ```

- No macOS/Linux:

  ```bash
  source venv/bin/activate
  ```

### 3. Instalar as Dependências

Com o ambiente virtual ativado, instale as dependências necessárias a partir do arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 4. Executar o Script de Análise

Para realizar a análise dos dados eleitorais e gerar os outputs, execute o seguinte comando:

```bash
python analise_eleitoral.py
```

### 5. Executar o Dashboard

Após a execução do script de análise, você pode gerar o dashboard interativo com o Streamlit. Para isso, execute o seguinte comando:

```bash
streamlit run dashboard.py
```

Isso abrirá uma nova aba em seu navegador padrão com a interface do dashboard.

## Contribuição

Sinta-se à vontade para contribuir com o projeto! Você pode abrir issues ou pull requests conforme necessário.

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Se tiver dúvidas ou precisar de mais informações, entre em contato!
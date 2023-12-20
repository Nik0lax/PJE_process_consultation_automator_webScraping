# Automatizador de Consulta de Processos PJE TR1 Federal (Python Web Scraping)

Projeto criado utilizando apenas a linguagem Python e as bibliotecas Selenium, OpenPyXl, Os, Tkinter e CustomTkinter.

**Resumo**: O método de Web Scraping foi utilizado para acessar o site governamental PJE (Processo Judicial Eletrônico) do TR1 (Tribunal Regional 1) e extrair todos os dados de cada processo em que um advogado trabalhou neste tribunal. Após a extração, os dados são formatados e inseridos em um arquivo xlsx, ficando disponíveis na área de trabalho do usuário.

Além disso, foi desenvolvida uma Interface Gráfica, onde o usuário pode inserir os dados utilizados para a consulta: O número da OAB (Identificação do Advogado Brasileiro) e a sigla do estado em que trabalham.

Todos os dados utilizados são de conhecimento público e não violam a LGPD.

## 📄 Referência

- [Documentação CustomTkinter](https://pypi.org/project/customtkinter/0.3/)
- [Documentação OpenPyXl](https://openpyxl.readthedocs.io/en/stable/)
- [Documentação Selenium](https://www.selenium.dev/pt-br/documentation/webdriver/getting_started/)
- [Site PJE TR1](https://pje1g.trf1.jus.br/consultapublica/ConsultaPublica/listView.seam)
- [Site OAB (Para adquirir a identificação de um advogado)](https://cna.oab.org.br/)
  
## 🛠️ Requisitos
Para executar este projeto, será necessário criar um ambiente virtual e instalar as dependências:

selenium
openpyxl
tkinter
customtkinter
PIL (Pillow)

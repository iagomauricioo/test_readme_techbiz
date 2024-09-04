<h1 align="center">Desafio TechBiz</h1>

###

<div align="center">
  <img height="200" src="https://image.slidesharecdn.com/institucionaltechbizforensedigital-100701092914-phpapp02/85/institucional-techbiz-forense-digital-1-320.jpg?cb=1670119558"  />
</div>

###

<h1 align="center">Em parceria com Roga DX 2024</h1>

###

<div align="center">
  <img height="100" src="https://github.com/user-attachments/assets/bb8d4ffb-df43-4643-8f96-386d841c5548"  />
</div>

###

<h2 align="left">Equipe AIr-Force 🤖</h2>

###

<h4 align="left">- Aldo Nunes<br>- Daniel Correia<br>- Iago Mauricio</h4>

###

<h3 align="left">Sobre o projeto</h3>

###

<p align="left">Este projeto visa resolver o desafio de transformar inputs de dados em diversos formatos (XML, JSON, CSV, HTML, etc.) em um modelo JSON padronizado. Dada a complexidade e a variabilidade desses formatos, uma abordagem tradicional baseada em regras se mostraria insuficiente para lidar com as ambiguidades e a estrutura hierárquica dos dados.</p>

###



###

<h3 align="left">Exemplo de entrada de dados não tratados</h3>

```xml
<Products>
    <ID>123</ID>
    <Name>Product X</Name>
    <Price>100.0</Price>
    <LastUpdated>2023-09-01T12:00:00</LastUpdated>
    <ReviewedBy>John Doe</ReviewedBy>
    <InternalCode>PX100</InternalCode>
    <WarehouseLocation>Shelf A3</WarehouseLocation>
    <Notes>N/A</Notes>
</Products>
<Products>
    <ID>456</ID>
    <Price>150.0</Price>
    <Name>Product Y</Name>
    <LastUpdated>2023-09-01T12:00:00</LastUpdated>
    <ReviewedBy>Jane Doe</ReviewedBy>
    <InternalCode>PY150</InternalCode>
    <WarehouseLocation>Shelf B5</WarehouseLocation>
    <Notes>Special Handling Required</Notes>
</Products>
```



<h3 align="left">Exemplo de JSON padronizado</h3>

```json
{
    "sinapses.Products": [
        {
            "sinapses.Name": "Product X",
            "sinapses.Price": 100.0
        },
        {
            "sinapses.Name": "Product Y",
            "sinapses.Price": 150.0
        }
    ]
}
```

<h3 align="left">Tecnologias utilizadas</h3>

###

<div align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=black&style=for-the-badge" height="40" alt="jupyter logo"  />
  <img width="12" />
  <img src="https://img.shields.io/badge/ChatGPT-74aa9c?logo=openai&logoColor=white" height="40" alt="ChatGPT logo"  />
  
</div>

<h3 align="left">Arquitetura criada e utilizada</h3>

<div align="center">
  <img height="200" src="https://github.com/user-attachments/assets/066cebf1-573b-4b2c-bc68-f47b1ec2930f"  />
</div>

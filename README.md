# Lab_Sec_SOC

TheHive, Cortex e MISP usando contêineres Docker aproveitando a ferramenta Docker Compose e usando .YAML para definir nossa implantação.
Para recapitular, TheHive é uma plataforma de resposta a incidentes de segurança (SIRP) usada por profissionais de segurança cibernética para gerenciar 
e rastrear incidentes caso a caso. Cortex e MISP são plataformas que nos fornecem inteligência após a análise de quaisquer observáveis, como endereços IP,
nomes de host, etc., que possamos ver durante o incidente.
Existem muitas abordagens para instalar essas plataformas, no entanto, para uma configuração de laboratório rápida e fácil, optei por implantar 
contêineres docker para cada serviço.

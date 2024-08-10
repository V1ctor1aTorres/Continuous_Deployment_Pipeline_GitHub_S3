# Criando um pipeline com CodePipeline, Github e S3.

[AWS Project: Build a Game with a Continuous Deployment Pipeline from GitHub to S3 | AWS Tutorial](https://www.youtube.com/watch?v=biYVW1TMYAU)

##  Fazer um fork do repositorio com o codigo de um jogo da memoria:
- [Respositorio](https://github.com/tinytechnicaltutorials/codepipeline-s3-game)

## Criar e configurar um bucket S3:
- Nome e habilitar acesso público
<img src="https://github.com/V1ctor1aTorres/Continuous_Deployment_Pipeline_GitHub_S3/blob/main/images/criar_bucket_1.png">
<img src="https://github.com/V1ctor1aTorres/Continuous_Deployment_Pipeline_GitHub_S3/blob/main/images/criar_bucket_2.png">
  
- Bucket criado
<img src="https://github.com/V1ctor1aTorres/Continuous_Deployment_Pipeline_GitHub_S3/blob/main/images/bucket_criado.png">
  
- Habilitar hospedagem de site estatico
<img src="https://github.com/V1ctor1aTorres/Continuous_Deployment_Pipeline_GitHub_S3/blob/main/images/hospedar_site.png">

- Adicionar uma politica de acesso público de leitura
<img src="https://github.com/V1ctor1aTorres/Continuous_Deployment_Pipeline_GitHub_S3/blob/main/images/politica.png">
  
## Configurar o CodePipeline: pegar o código do github e colocar no bucket
- Criar pipeline:
<img src="https://github.com/V1ctor1aTorres/Continuous_Deployment_Pipeline_GitHub_S3/blob/main/images/configuracao_pipeline_1.png">
<img src="https://github.com/V1ctor1aTorres/Continuous_Deployment_Pipeline_GitHub_S3/blob/main/images/configuracao_pipeline_2.png">
<img src="https://github.com/V1ctor1aTorres/Continuous_Deployment_Pipeline_GitHub_S3/blob/main/images/configuracao_pipeline_3.png">
  
- Pipeline criado:
<img src="https://github.com/V1ctor1aTorres/Continuous_Deployment_Pipeline_GitHub_S3/blob/main/images/pipeline_criado.png">  
  
## Testes:
- Web site
<img src="https://github.com/V1ctor1aTorres/Continuous_Deployment_Pipeline_GitHub_S3/blob/main/images/teste_site.png">
  
- Adicionando mudanças no site
<img src="https://github.com/V1ctor1aTorres/Continuous_Deployment_Pipeline_GitHub_S3/blob/main/images/teste_atualizacao_site.png">

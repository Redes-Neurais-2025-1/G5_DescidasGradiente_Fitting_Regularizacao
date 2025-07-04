# 🧠 G5 – Descidas de Gradiente, Overfitting/Underfitting e Regularização

Este repositório contém o material de apoio da apresentação do Grupo 5 na disciplina **Tópicos em Engenharia da Computação II – Fundamentos de Redes Neurais**.  
Abordamos três eixos fundamentais no treinamento de modelos de aprendizado de máquina:

---

## 📘 Conteúdo Apresentado

### 🔽 1. Descidas de Gradiente
Estudo comparativo entre os três principais tipos de algoritmos de otimização via gradiente:

- **Batch Gradient Descent**  
- **Stochastic Gradient Descent (SGD)**  
- **Mini-Batch Gradient Descent**

Inclui definições, vantagens, desvantagens, e quando cada técnica é mais apropriada.

---

### 📉 2. Overfitting e Underfitting
Análise dos problemas relacionados à **generalização de modelos**, com foco nos conceitos:

- **Viés e Variância**  
- Diagnóstico por curvas de erro  
- Efeitos no desempenho do modelo

---

### 🛡️ 3. Técnicas de Regularização
Apresentação das principais abordagens para reduzir o overfitting e melhorar a generalização:

- Regularização **L1 (Lasso)** e **L2 (Ridge)**
- **Dropout**
- **Early Stopping**
- Técnicas auxiliares como normalização e data augmentation

---

## 📂 Estrutura do Repositório

```plaintext
G5_DescidasGradiente_Fitting_Regularizacao
│
├─ README.md
│
├─ documentos/
│   ├─ apresentacao.pdf
│   ├─ apresentacao.pptx
│   ├─ documentacao.pdf
│   └─ documentacao.docx
│
└─ codigo/
│   ├─ Data
│   ├─ 1.GRADIENTE_BACH.ipynb
│   ├─ 2.GRADIENTE_ESTOCASTICO.ipynb
│   └─ 3.GRADIENTE_MINI_BATCH.ipynb
│   └─ FITTING_SIMULATION_WITH_REGULARIZATION.ipynb
```


## Reconhecimentos e Direitos Autorais

@autor: [Filipe das Chagas Pinheiro e Guilherme Roberto Matos Silva]  
@contato: [filipe.pinheiro@discente.ufma.br - matos.guilherme@discente.ufma.br]  
@data última versão: [13/06/2025]  
@versão: 1.0  
@outros repositórios: [https://github.com/filipe-pinheiro - https://github.com/guilherme-rms-cv]  
@Agradecimentos: Universidade Federal do Maranhão (UFMA), Professor Doutor Thales Levi Azevedo Valente, e colegas de curso.

---

## Copyright / License

Este material é resultado de um trabalho acadêmico para a disciplina EECP0053 -  
**TÓPICOS EM ENGENHARIA DA COMPUTAÇÃO II - FUNDAMENTOS DE REDES NEURAIS**,  
sob a orientação do professor Dr. Thales Levi Azevedo Valente, semestre letivo 2025.1,  
curso Engenharia da Computação, na Universidade Federal do Maranhão (UFMA).  

Todo o material sob esta licença é software livre: pode ser usado para fins acadêmicos e comerciais sem nenhum custo.  
Não há papelada, nem royalties, nem restrições de "copyleft" do tipo GNU.  

Ele é licenciado sob os termos da **Licença MIT**, conforme descrito abaixo, e, portanto, é compatível com a GPL e também se qualifica como software de código aberto.  
É de domínio público. O espírito desta licença é que você é livre para usar este material para qualquer finalidade, sem nenhum custo.  
O único requisito é que, se você usá-lo, nos dê crédito.

---

**Licenciado sob a Licença MIT.**

Permissão é concedida, gratuitamente, a qualquer pessoa que obtenha uma cópia deste software e dos arquivos de documentação associados (o "Software"),  
para lidar no Software sem restrição, incluindo sem limitação os direitos de usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias do Software,  
e permitir pessoas a quem o Software é fornecido a fazê-lo, sujeito às seguintes condições:

> Este aviso de direitos autorais e este aviso de permissão devem ser incluídos em todas as cópias ou partes substanciais do Software.

O SOFTWARE É FORNECIDO "COMO ESTÁ", SEM GARANTIA DE QUALQUER TIPO,  
EXPRESSA OU IMPLÍCITA, INCLUINDO MAS NÃO SE LIMITANDO ÀS GARANTIAS DE COMERCIALIZAÇÃO,  
ADEQUAÇÃO A UM DETERMINADO FIM E NÃO INFRINGÊNCIA.  
EM NENHUM CASO OS AUTORES OU DETENTORES DE DIREITOS AUTORAIS SERÃO RESPONSÁVEIS  
POR QUALQUER RECLAMAÇÃO, DANOS OU OUTRA RESPONSABILIDADE,  
SEJA EM AÇÃO DE CONTRATO, TORT OU OUTRA FORMA,  
DECORRENTE DE, FORA DE OU EM CONEXÃO COM O SOFTWARE OU O USO OU OUTRAS NEGOCIAÇÕES NO SOFTWARE.

Para mais informações sobre a Licença MIT:  
https://opensource.org/licenses/MIT

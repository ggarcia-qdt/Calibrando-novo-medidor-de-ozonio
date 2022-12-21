# Calibrando-novo-medidor-de-ozonio

# <font color='royalblue' style='font-size: 30px;'>Calibração de medidor de ozônio (Dissertação de Mestrado)</font>

## Descrição e objetivos

Este projeto apresenta uma aplicação de modelo de aprendizado de máquina (regressão linear) para realização de previsões na área de química ambiental.

O contexto desta aplicação é o desenvolvimento de um novo método de análise química (Tubo de Difusão) para medir a concentração de ozônio na atmosfera, tópico de minha Dissertação de Mestrado no Instituto de Química - Unesp, campus de Araraquara.

Os resultados do novo método foram comparados com os resultados do método de referência (UV) pelo uso de regressão linear.

O modelo produzido pode permitir dois tipos de previsões: 1) Prever o resultado do tubo de difusão quando se conhece o valor de referência ou 2) Prever o valor de referência (tido como o valor "real" da concentração de ozônio) quando apenas o resultado do tubo de difusão está disponível (conceito de curva de calibração na área de análises químicas).

Ambos os tipos de previsões foram desenvolvidos neste documento para exemplificar a aplicação típica de modelos de aprendizado de máquina em química ambiental, bem como salientar sua semelhança com resoluções de problemas de negócio pela aplicação de regressão linear.

#### Fonte dos dados

Os dados estão disponíveis na Dissertação de Mestrado, link: https://repositorio.unesp.br/handle/11449/97808 


#### Referência bibliográfica

Garcia, G. Construção e calibração de amostrador passivo para determinação de ozônio troposférico. Dissertação de Mestrado. Araraquara, 2009.

### Principais observações

Tal aplicação de modelo de regressão linear permite a realização de previsões sobre a concentração de um poluente atmosférico.

Mas principalmente, também permite comparar a performance de um novo método recentemente desenvolvido com um método já bem conhecido e aceito pela indústria da qualidade do ar.

Esta mesma estrutura de análise estatística poderia ser replicada para resolução de diversos problemas de negócio em que hajam correlações lineares entre variáveis e que se deseje fazer previsões de cenários específicos.

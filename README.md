# Crime Prediction - Regression

# Dataset Information

The database contains monthly quantitative values of preventive actions carried out by the military police in Campo Grande - MS. Based on the values of these preventive actions, the goal of the regression model is to try to predict the number of crimes that will occur in the coming months.

**Attribute Information:-**

--preventive actions--

ANO                                                                                           
MÊS                                                                                           
ÁREA                                                                                          
UNIDADE                                                                                       
OPERAÇÃO BLITZ                                                                                
OPERAÇÃO EM APOIO A OUTRO ÓRGÃO                                                               
OPERAÇÃO POLICIAL                                                                             
PESSOAS ABORDADAS                                                                             
VEÍCULOS ABORDADOS - DUAS RODAS                                                               
VEÍCULOS ABORDADOS - QUATRO RODAS                                                             
ARMA BRANCA                                                                                   
ARMAS DE FOGO                                                                                 
VEÍCULOS DUAS RODAS RECUPERADOS                                                               
VEÍCULOS DUAS RODAS REMOVIDOS AO DETRAN/CIRETRAN (Por conta de fiscalização de trânsito)      
VEÍCULOS QUATRO RODAS RECUPERADOS                                                             
VEÍCULOS QUATRO RODAS REMOVIDOS AO DETRAN/CIRETRAN (Por conta de fiscalização de trânsito)    
MASCULINO - ADULTO - CONDUZIDO                                                                
MASCULINO - ADOLESCENTE - CONDUZIDO                                                           
FEMININO - ADULTO - CONDUZIDO                                                                 
FEMININO - ADOLESCENTE - CONDUZIDO                                                            
MASCULINO - ADULTO FORAGIDO (Nº de presos por mandado de prisão/evasão)                       
MASCULINO - ADOLESCENTE FORAGIDO (Nº de apreendidos por mandado de apreensão/evasão)          
FEMININO - ADULTO FORAGIDO (Nº de presos por mandado de prisão/evasão)                        
FEMININO - ADOLESCENTE FORAGIDO (Nº de apreendidos por mandado de apreensão/evasão)           
Nº DE OCORRÊNCIAS QUE RESULTARAM EM AUTO DE PRISÃO FLAGRANTE DELITO                           
Nº DE OCORRÊNCIAS QUE RESULTARAM EM T.C.O                                                     
NOTIFICAÇÕES DE TRÂNSITO - (Nº de Infrações diversas - AIPs)                                  
POLICIAMENTO EM EVENTO                                                                        
POLICIAMENTO ESCOLAR - RONDAS PREVENTIVAS                                                     
POSTOS FIXOS (PB)                                                                             
RONDAS PREVENTIVAS EM ÁREA RURAL                                                              
RONDAS PREVENTIVAS EM ÁREA URBANA   

--possible target attribute--

ROUBO                                                                                         
HOMICIDIO DOLOSO                                                                                                             
FURTO                                                                                         
ROUBO DE VEICULO                                                                              
ROUBO EM RESIDENCIA                                                                           
ROUBO A COMERCIO                                                                              
FURTO EM RESIDENCIA                                                                           
FURTO DE VEICULO                                                                              
DROGAS                                                                                        
PERTURBAÇÃO  

--target attribute used in the model-- 

ROUBO EM VIA URBANA 
     

# Libraries

<li>pandas
<li>numpy
<li>matplotlib
<li>seaborn
<li>scikit-learn

# Algorithms

<li>Linear Regression
<li>Random Forest Regressor

  
**Best Model Results:** 
MAE: 12.79
MSE: 238.48
RMSE: 15.44
R: 0.35
MAPE: 21.05

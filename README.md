# Desafio Preditivo

## About Dataset

This dataset is designed for the task of fault detection and predictive maintenance in industrial systems using data from digital twin (DT) technologies. It includes sensor data, operational parameters, environmental metrics, and machine health information over a 5-year period from January 2019 to January 2024, recorded hourly.

The dataset simulates a real-world industrial setting, incorporating a variety of features related to machinery performance, maintenance events, and environmental conditions. It captures unbalanced fault occurrences across multiple severity levels, making it a perfect resource for exploring predictive maintenance models, machine learning algorithms, and advanced analytics techniques in industrial contexts.

The dataset is ideal for training and evaluating models aimed at fault detection, predictive maintenance, anomaly detection, and time series forecasting in complex industrial environments. Users can explore how different factors impact machine health and predict future failures using advanced machine learning and deep learning models.

## Features

The dataset consists of 38 features that span across sensor data, operational metrics, machine health indicators, environmental factors, and fault information. Below is a detailed description of the dataset features:

## Feature Name Description

Datetime Timestamp of the recorded data (hourly from Jan 2019 to Jan 2024).
Vibration_Level Vibration levels of the machine (measured in arbitrary units).
Temperature_Readings Internal machine temperature readings (in degrees Celsius).
Pressure_Data Pressure measurements (in Pascals).
Acoustic_Signals Sound signals produced by the machine (in decibels).
Humidity_Levels Humidity levels within the machine environment (in percentage).
Motor_Speed Machine motor speed (in RPM).
Torque_Data Torque applied by the motor (in Nm).
Energy_Consumption Energy consumption of the machine (in kWh).
Production_Rate Rate of production (in units per hour).
Tool_Wear_Rate Tool wear rate (in percentage).
Machine_Utilization_Rate Percentage of time the machine is in operation (in percentage).
Cycle_Time_Per_Operation Time taken to complete one operational cycle (in seconds).
Idle_Time Percentage of time the machine remains idle (in percentage).
Machine_Load_Percentage Load percentage on the machine (in percentage).
Ambient_Temperature Surrounding ambient temperature (in degrees Celsius).
Humidity Ambient humidity level (in percentage).
Air_Quality_Index Air quality index in the environment (scale from 0 to 500).
Machine_Health_Index Health index of the machine (on a scale from 0 to 100).
Failure_Mode_Indicators Binary indicator of failure modes (0 = no failure, 1 = failure).
Maintenance_Logs Binary indicator of scheduled or unscheduled maintenance events.
Previous_Fault_Occurrences Binary indicator if a fault occurred in the recent past (0 = no, 1 = yes).
Predictive_Maintenance_Scores Predictive score for upcoming maintenance events (scale from 0 to 100).
Component_Degradation_Index Degradation index of machine components (scale from 0 to 100).
Real_Time_Performance_Index Real-time performance index of the machine (scale from 0 to 100).
Machine_Start_Stop_Events Binary indicator of machine start/stop events (0 = no, 1 = yes).
Downtime_Incidents Binary indicator of machine downtime incidents (0 = no, 1 = yes).
Fault_Trigger_Timestamps Binary indicator of fault-triggering events (0 = no, 1 = yes).
Controller_Setpoints Setpoint values for machine controllers.
Actual_vs_Setpoint_Values Difference between actual values and setpoints.
Alarm_Trigger_Data Binary indicator for alarm events (0 = no, 1 = yes).
Repair_Logs Binary indicator of machine repairs (0 = no, 1 = yes).
Spare_Part_Usage Usage of spare parts during maintenance (in units).
Anomaly_Scores Anomaly detection scores (scale from 0 to 100).
Fault_Probability Probability of a fault occurring (scale from 0 to 100).
Operator_Shift_Data Operator shift information (1 = morning, 2 = afternoon, 3 = night).
Quality_Control_Test_Results Results of quality control tests (scale from 0 to 100).
Fault_Diagnosis Target label for fault diagnosis (0 = No Fault, 1 = Minor Fault, 2 = Moderate Fault, 3 = Severe Fault, 4 = Critical Fault).

## Target Variable

Fault_Diagnosis: A multiclass label representing the severity of the fault in the system, ranging from No Fault to Critical Fault. This is the target variable for building classification models.

## Use Cases

Fault detection and classification.
Predictive maintenance.
Anomaly detection.
Time series forecasting.
Machine health monitoring.

This dataset is useful for machine learning practitioners, data scientists, and researchers interested in applying AI and predictive analytics to industrial systems for fault detection and operational optimization.

---

## Sobre o Conjunto de Dados

Este conjunto de dados foi desenvolvido para tarefas de detecção de falhas e manutenção preditiva em sistemas industriais, utilizando dados de tecnologias de gêmeos digitais (DT). Inclui dados de sensores, parâmetros operacionais, métricas ambientais e informações sobre a integridade das máquinas, registrados a cada hora, durante um período de 5 anos, de janeiro de 2019 a janeiro de 2024.

O conjunto de dados simula um ambiente industrial real, incorporando uma variedade de recursos relacionados ao desempenho das máquinas, eventos de manutenção e condições ambientais. Ele captura ocorrências de falhas desbalanceadas em vários níveis de gravidade, tornando-se um recurso perfeito para explorar modelos de manutenção preditiva, algoritmos de aprendizado de máquina e técnicas avançadas de análise em contextos industriais.

O conjunto de dados é ideal para treinar e avaliar modelos voltados para detecção de falhas, manutenção preditiva, detecção de anomalias e previsão de séries temporais em ambientes industriais complexos. Os usuários podem explorar como diferentes fatores impactam a integridade das máquinas e prever falhas futuras usando modelos avançados de aprendizado de máquina e aprendizado profundo.

## Recursos

O conjunto de dados consiste em 38 recursos que abrangem dados de sensores, métricas operacionais, indicadores de integridade das máquinas, fatores ambientais e informações sobre falhas. Abaixo, uma descrição detalhada dos recursos do conjunto de dados:

## Nome do Recurso Descrição

Data e hora Carimbo de data e hora dos dados registrados (por hora, de janeiro de 2019 a janeiro de 2024).
Vibration_Level Níveis de vibração da máquina (medidos em unidades arbitrárias).
Temperature_Readings Leituras de temperatura interna da máquina (em graus Celsius).
Pressure_Data Medições de pressão (em Pascal).
Acoustic_Signals Sinais sonoros produzidos pela máquina (em decibéis).
Humidity_Levels Níveis de umidade no ambiente da máquina (em porcentagem).
Motor_Speed ​​Velocidade do motor da máquina (em RPM).
Torque_Data Torque aplicado pelo motor (em Nm).
Energy_Consumption Consumo de energia da máquina (em kWh).
Production_Rate Taxa de produção (em unidades por hora).
Tool_Wear_Rate Taxa de desgaste da ferramenta (em porcentagem).
Machine_Utilization_Rate Porcentagem de tempo em que a máquina está em operação (em porcentagem).
Cycle_Time_Per_Operation Tempo gasto para completar um ciclo operacional (em segundos).
Idle_Time Porcentagem de tempo que a máquina permanece ociosa (em porcentagem).
Machine_Load_Percentage Porcentagem de carga na máquina (em porcentagem).
Ambient_Temperature Temperatura ambiente (em graus Celsius).
Humidity Nível de umidade ambiente (em porcentagem).
Air_Quality_Index Índice de qualidade do ar no ambiente (escala de 0 a 500).
Machine_Health_Index Índice de integridade da máquina (em uma escala de 0 a 100).
Failure_Mode_Indicators Indicador binário de modos de falha (0 = sem falha, 1 = falha).
Maintenance_Logs Indicador binário de eventos de manutenção programados ou não programados.
Previous_Fault_Occurrences Indicador binário se uma falha ocorreu recentemente (0 = não, 1 = sim).
Predictive_Maintenance_Scores Pontuação preditiva para eventos de manutenção futuros (escala de 0 a 100).
Component_Degradation_Index Índice de degradação dos componentes da máquina (escala de 0 a 100).
Real_Time_Performance_Index Índice de desempenho em tempo real da máquina (escala de 0 a 100).
Machine_Start_Stop_Events Indicador binário de eventos de partida/parada da máquina (0 = não, 1 = sim).
Downtime_Incidents Indicador binário de incidentes de tempo de inatividade da máquina (0 = não, 1 = sim).
Fault_Trigger_Timestamps Indicador binário de eventos que acionam falhas (0 = não, 1 = sim).
Controller_Setpoints Valores de ponto de ajuste para controladores de máquina.
Actual_vs_Setpoint_Values ​​Diferença entre valores reais e pontos de ajuste.
Alarm_Trigger_Data Indicador binário para eventos de alarme (0 = não, 1 = sim).
Repair_Logs Indicador binário de reparos de máquinas (0 = não, 1 = sim).
Spare_Part_Usage Uso de peças de reposição durante a manutenção (em unidades).
Anomaly_Scores Pontuações de detecção de anomalias (escala de 0 a 100).
Fault_Probability Probabilidade de ocorrência de uma falha (escala de 0 a 100).
Operator_Shift_Data Informações sobre o turno do operador (1 = manhã, 2 = tarde, 3 = noite).
Quality_Control_Test_Results Resultados dos testes de controle de qualidade (escala de 0 a 100).
Fault_Diagnosis Rótulo de destino para diagnóstico de falhas (0 = Sem Falha, 1 = Falha Leve, 2 = Falha Moderada, 3 = Falha Grave, 4 = Falha Crítica).

## Variável de destino

Fault_Diagnosis: Um rótulo multiclasse que representa a gravidade da falha no sistema, variando de Sem Falha a Falha Crítica. Esta é a variável alvo para a construção de modelos de classificação.

## Casos de Uso

Detecção e classificação de falhas.
Manutenção preditiva.
Detecção de anomalias.
Previsão de séries temporais.
Monitoramento da saúde da máquina.

Este conjunto de dados é útil para profissionais de aprendizado de máquina, cientistas de dados e pesquisadores interessados ​​em aplicar IA e análise preditiva a sistemas industriais para detecção de falhas e otimização operacional.

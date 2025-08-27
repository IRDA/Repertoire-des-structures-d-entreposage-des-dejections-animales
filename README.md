# Localisation des structures d’entreposage de déjections animales au Québec

Ce projet présente une application et un modèle développés à l’IRDA par Cédric Bouffard, agr. et Louis Thériault. L’objectif est de localiser automatiquement les structures d’entreposage de déjections animales (fosses) à partir d’orthophotos couvrant l’ensemble du sud du Québec.  

Le modèle utilisé repose sur l’architecture **ResNet-50**, entraînée sur des données annotées provenant d’orthophotos. Une fois entraîné, il a été appliqué à grande échelle afin de détecter les fosses sur tout le territoire agricole.  

Chaque structure détectée est enrichie de propriétés spatiales et contextuelles permettant d’en faciliter l’interprétation : distance aux routes, aux parcelles agricoles et aux plans d’eau, hauteur estimée et information de zonage.  

Les résultats sont accessibles via une **application web interactive** qui permet de visualiser les fosses détectées et leurs caractéristiques, ainsi que d’explorer leur répartition sur l’ensemble du territoire analysé.  

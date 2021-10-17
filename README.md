# sap-api-integrations-outbound-delivery-events  
sap-api-integrations-outbound-delivery-events は、外部システム(特にエッジコンピューティング環境)をSAPと統合することを目的として、SAP上で発生した出荷イベントを、SAP API で出力するマイクロサービスです。  
sap-api-integrations-outbound-delivery-events には、サンプルのAPI Json フォーマットが含まれています。  

## 動作環境
sap-api-integrations-outbound-delivery-events は、主にエッジコンピューティング環境における動作にフォーカスしています。  
使用する際は、事前に下記の通り エッジコンピューティングの動作環境（推奨/必須）を用意してください。  
・ エッジ Kubernetes  （推奨）  
・ AION のリソース  （推奨）  
・ OS: LinuxOS （必須）  
・ CPU: ARM/AMD/Intel（いずれか必須）    
 
<img src="https://github.com/apigee/edge-launchpad/blob/master/images/edge-launchpad-wall-image.png" alt=""> 

# Apigee
manage api tool - by google </br>
link to COURSERA : https://www.coursera.org/specializations/apigee-api-gcp?action=enroll

<pre>

Doc start:
https://docs.apigee.com/how-to-guides/how-to-guides-introduction</br>
https://apidocs.apigee.com/apis

סרטוני הסברה apigee:
https://cloud.google.com/blog/products/api-management/getting-started-with-apigee-api-management
נושאים : 
policies:  
Quota –  https://docs.apigee.com/api-platform/reference/policies/quota-policy
Verify-api-key – מפתח לשירות שימוש עי Query param וכו  https://docs.apigee.com/api-platform/reference/policies/verify-api-key-policy
assignMessage -  https://docs.apigee.com/api-platform/reference/policies/assign-message-policy
 
סרטוני הסברה מורחבים : 
https://www.youtube.com/watch?v=_B_y0gIT86o&list=PLsWqc60hQz4e-dV4sXOmmqAdB_JIfpl2M&index=7



proxy flows –  add verb+path to execute

</pre>

TLS- https://www.internetsociety.org/deploy360/tls/basics/?gclid=EAIaIQobChMI6aHj09yC-QIVDJ53Ch2YbQpLEAAYASAAEgK9bfD_BwE
</br>

### Filtering Options - Endpoints of resource collections should allow filtering by using query parameters.
<pre>
Filtering type	                Operator suffix name     	Format            	Example
Equality(=)	  	                                         {fieldName}=values	      amount=400
Greater than (>)	                        MIN           	{fieldName}MIN=value	    amountMIN=400
Less than (<)	                           MAX	           {fieldName}MAX=value 	   firstPaymentDateMAX=2020-19-02T14:30:00.000Z
Greater than or equal to (>=)	          MINEQ	          {fieldName}MINEQ=value	  amountMINEQ=400
Less than or equal to (<=)             	MAXEQ	          {fieldName}MAXEQ=value	  amountMAXEQ=900
Not equal to (!=)	                      NOT	            {fieldName}NOT=values	   statusNOT=4

</pre>

enrichments:</br>https://github.com/OAI/OpenAPI-Specification/blob/main/versions/3.0.0.md</br>
Web API Design:https://cloud.google.com/files/apigee/apigee-web-api-design-the-missing-link-ebook.pdf</br>
Load balancing across backend servers :https://cloud.google.com/apigee/docs/api-platform/deploy/load-balancing-across-backend-servers</br>
About environments and environment groups: https://cloud.google.com/apigee/docs/api-platform/fundamentals/environments-overview

gcloud CLI overview: https://cloud.google.com/sdk/gcloud




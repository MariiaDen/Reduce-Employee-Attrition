<h1><span style="font-weight: 400; color: #3366ff;">Microsoft Azure ML Project Showcase Challenge</span></h1>
<p><span style="font-weight: 400;">This project is presented as a final showcase for the </span><em><span style="font-weight: 400;">Udacity Microsoft Scholarship Foundation course Nanodegree Program</span></em><span style="font-weight: 400;"> and aim to predict the probability of attrition of an employee, based on a model trained on a dataset containing information such as:</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Personal information</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Time tracking</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Management survey</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Personal survey</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Objective last year metrics</span></li>
</ul>
<p><span style="font-weight: 400;">The original intent is to suggest </span><span style="font-weight: 400;">to the management what changes they should make to their workplace, in order to get most of their employees to stay.</span></p>
<h1><span style="font-weight: 400;">Project description</span></h1>
<p><span style="font-weight: 400;">Companies worldwide always try to get the best human resources they can in order to achieve their goals and ensure the business continuity. At the same time, staff turnover remains a big problem.&nbsp;</span></p>
<p><span style="font-weight: 400;">According to LinkedIn [</span><a href="https://business.linkedin.com/talent-solutions/blog/trends-and-research/2018/the-3-industries-with-the-highest-turnover-rates"><span style="font-weight: 400;">Link</span></a><span style="font-weight: 400;">], an average annual worldwide employee turnover rate is 10.9%. At the same time, some industries, such as Technology or Hospitality experience even higher rates, remaining at 13+%.&nbsp;</span></p>
<p><span style="font-weight: 400;">Employee turnover is one of the major HR metrics, and is always used in the negative context, since it becomes an expensive problem. According to The Society for Human Resource Management (SHRM) [</span><a href="https://www.shrm.org/hr-today/trends-and-forecasting/special-reports-and-expert-views/Documents/Retaining-Talent.pdf"><span style="font-weight: 400;">Link</span></a><span style="font-weight: 400;">] the average replacement of a salaried employee can cost from six to nine months&rsquo; salary, and is dependent on the job level employee has. Other studies name the figures to be significantly higher - as much as twice the employee&rsquo;s annual salary, especially for high-earner or executive level employees [</span><a href="https://mnwi.usi.com/Resources/Resource-Library/Resource-Library-Article/ArtMID/666/ArticleID/782"><span style="font-weight: 400;">Link</span></a><span style="font-weight: 400;">].</span></p>
<p><span style="font-weight: 400;">At the same time, such topics as inclusiveness and diversity are addressed by most of the companies - when hiring people, companies strive for 50-50 in terms of gender, and diversity in terms of nationalities and age. At the same time, we believe that analysis of leavers statistics could reveal some internal problems, such as organizational problems, ineffective employee recognition, lack of two-way communication, a toxic or non-inclusive environment.&nbsp;</span></p>
<p><span style="font-weight: 400;">Employee leaving is usually an unexpected event, therefore the main idea behind this project is to use certain metrics collected about the employees to:</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">predict the possibility of employee leaving the company;</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">determine what are the main reasons for employees to leave;</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">ideally: understand whether the reasons have anything to do with the social side of the work environment.&nbsp;&nbsp;</span></li>
</ul>
<p><span style="font-weight: 400;">From the results of this study other companies can:</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">identify which statistics should they collect and pay attention to;&nbsp;</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">apply these learnings and based on it study their current situation;&nbsp;</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">create a strategic plan on how to lower the employee turnover rate.</span></li>
</ul>
<h2><span style="font-weight: 400;">Authors</span></h2>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Mariia D. - </span><a href="https://github.com/MariiaDen"><span style="font-weight: 400;">https://github.com/MariiaDen</span></a></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Enrico D. - </span><a href="https://github.com/edab"><span style="font-weight: 400;">https://github.com/edab</span></a><span style="font-weight: 400;">&nbsp;</span></li>
</ul>
<h2><span style="font-weight: 400;">DataSet</span></h2>
<p><span style="font-weight: 400;">The dataset used for this project is the </span><em><span style="font-weight: 400;">HR Analytics Case Study</span></em><span style="font-weight: 400;"> by Vijay Choudhary available through Kaggle [</span><a href="https://www.kaggle.com/vjchoudhary7/hr-analytics-case-study"><span style="font-weight: 400;">Link</span></a><span style="font-weight: 400;">].</span></p>
<h1><span style="font-weight: 400;">Project implementation</span></h1>
<p><span style="font-weight: 400;">The implementation is based on the Microsoft Azure ML technology, using the </span><em><span style="font-weight: 400;">Azure Studio Classic</span></em><span style="font-weight: 400;"> tool accessible from this </span><a href="https://studio.azureml.net/"><span style="font-weight: 400;">link</span></a><span style="font-weight: 400;">.</span></p>
<p><span style="font-weight: 400;">For more details you can <a href="report.pdf">reference to the Report</a> attached to this submittion, containing Azure ML implementation and detailed description.</span></p>
<h1><span style="font-weight: 400;">Project Criterias</span></h1>
<h2><span style="font-weight: 400;">Innovation and creativity</span></h2>
<p><span style="font-weight: 400;">Taking into consideration labor turnover, and looking at it as at the measurement of the work environment - in terms of inclusiveness and diversity is a new idea that is proposed in this work. Companies already look at the metrics like gender equality when hiring people, but we propose to take a closer look at the leavers, and to better analyze the data that relates to that. Our results showed that top five deciding parameters are:&nbsp;</span></p>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Marital status</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Age</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Years worked with the current manager</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Years worked at company</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Business travel frequency.</span></li>
</ul>
<h2><span style="font-weight: 400;">Impact and potential</span></h2>
<p><span style="font-weight: 400;">The project can be useful for every company - independently of the size or industry. Though the small startups might have difficulties collecting enough data, they can learn from the results of our research. The bigger companies can collect statistics about their employees and identify needed improvements as early as possible according to the result of the model predictions to keep their resources satisfied. Integrating this research into HR metrics analysis will help to save much time and money by preventing losing valuable employees, and making the working world better.&nbsp;</span></p>
<p><span style="font-weight: 400;">Azure ML is a perfect tool for this matter, and our experiment can be easily re-created by other specialists, who might not be that sound in programming or machine learning algorithms. Azure also offers friendly prices, which would make it possible for different companies to implement it without causing large costs.&nbsp;</span></p>
<h2><span style="font-weight: 400;">Responsible AI</span></h2>
<p><span style="font-weight: 400;">To make the project aligned with the AI ethics, we took care of applying the below Responsible AI principles:&nbsp;</span></p>
<ul>
<li style="font-weight: 400;"><strong>Inclusiveness </strong><span style="font-weight: 400;">- to empower everyone and engage people, the chosen dataset provides a very diverse data in terms of age and gender, as well as many other metrics. The results are also used to understand what are the reasons of people leaving, and in which fields the company has to become more inclusive, to remove the obstacles for people to work happily.&nbsp;</span></li>
<li style="font-weight: 400;"><strong>Transparency </strong><span style="font-weight: 400;">&nbsp;- the algorithm results are explanatory, and can be tracked. The features with the most significant impact are detected and listed.&nbsp;</span></li>
<li style="font-weight: 400;"><strong>Accountability </strong><span style="font-weight: 400;">- the individuals that use this system have to be accountable for using it. There must be a trust between employees and management/ HR - people have to believe and understand that the data collected is not going to be used against them, but on the contrary - used to support them. This can not be reached by AI, but only by the company&rsquo;s culture and individuals.&nbsp;</span></li>
<li style="font-weight: 400;"><strong>Fairness </strong><span style="font-weight: 400;">- the system treats everyone fairly and avoids affecting similarly situated groups of people in different ways. The tool is used to help people, and not penalize them. The dataset contains diverse data from different groups of people, including different departments, to avoid penalizing any subgroup.</span></li>
<li style="font-weight: 400;"><strong>Reliability &amp; Safety</strong><span style="font-weight: 400;"> - the system has to operate reliably, safely, and consistently under normal circumstances and in unexpected conditions, as originally designed. This system doesn&rsquo;t have any endpoints for external adversarial attacks (e.g. feeding the model with data that could harm the system). The dataset provided has a diverse data, and this is the responsibility of the company to collect the data without any adversarial amendments.&nbsp;</span></li>
<li style="font-weight: 400;"><strong>Privacy &amp; Security</strong><span style="font-weight: 400;"> - protecting privacy became one of the most important tasks. Especially since the GDPR (General Data Protection Regulation) came into effect, it is extremely important to have a consent about the collected private data, to use this data only for the pre-defined purpose, and to keep this data safe. Non-compliance can lead to high penalties and legal issues. Azure cloud takes care of safety of the platform and storage, but the security of data, access and endpoints is left to the user. Therefore, companies have to think carefully and take all needed measures to provide access to the data only to people, who need to see that data.&nbsp;</span></li>
</ul>
<h1><span style="font-weight: 400;">Results and Next Steps</span></h1>
<p><span style="font-weight: 400;">The results of the experiment have shown a very high accuracy - 97.8%, which means that we are able to predict whether an employee might be thinking of leaving a company. We could also define the features with the highest impact on an employee's decision to leave.&nbsp;</span></p>
<p><span style="font-weight: 400;">As the next step, there can be taken a closer look at those features, to get a better idea of the core problems. Two of the five top reasons to leave are years spent at the same company or with the same manager - this could mean that the company might offer some better development, or more diverse tasks, to keep employees engaged. On the other hand, this could also mean that management might need some training - to improve their communication and to establish a better rapport with their subordinates. For that maybe some further information needs to be collected. Here it is important to ensure that employees trust to give sincere feedback.&nbsp;</span></p>
<p><span style="font-weight: 400;">Business travel frequency, as the fifth reason for attrition, is a good sign to offer some more flexibility for working from home office. The top 2 reasons - marital status and age are the ones that need to get a closer look at. Why are these parameters so important? This can be a good start for further research.&nbsp;</span></p>
<p><span style="font-weight: 400;">From a technical point of view, the next step for our team could be deployment of the model as an online web-service.&nbsp;</span></p>

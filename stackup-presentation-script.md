# StackUp Presentation Script

## Slide 1 - Product Concept
Speaker: Aly

"Good day everyone. Ang i-introduce namin ay ang StackUp, a cloud-native team collaboration hub para sa small development teams and startups.

Makikita sa slide na ang main idea ng product ay pagsamahin ang deployment tracking, incident response, monitoring, at collaboration sa isang platform lang. So imbes na hiwa-hiwalay ang tools, nasa iisang workspace na lang siya.

Para sa target users naman, ito ay para sa small development teams, startups, freelance developers, at DevOps engineers or developers na kailangan ng mas organized na coordination.

Sa main purpose ng StackUp, gusto naming mabawasan ang tool fragmentation, mapabilis ang workflow, at mas mabilis makarespond kapag may issue o incident."

## Slide 2 - How It Leverages Emerging Technologies
Speaker: Dani and Aly

Dani:
"Dito natin makikita kung paano ginagamit ng StackUp ang emerging technologies, especially AI at cloud-native architecture."

Aly:
"Una, gamit ang AI, puwedeng mag-summarize ng incidents, mag-detect ng anomalies, mag-filter ng duplicate alerts, at mag-suggest ng possible root cause. Ibig sabihin, nababawasan ang operational noise at mas mabilis makapag-decide ang team.

Pangalawa, cloud-native ang architecture niya. Since microservices-based, containerized, at auto-scaling siya, mas okay siya for multi-tenant operations at real-time monitoring. So habang lumalaki ang users or workload, kaya pa rin niyang mag-scale.

Yung tatlong cards sa slide, pina-highlight lang nila na AI-powered ang operations, mas mabilis ang incident response, at modern cloud-native ang overall structure ng system."

## Slide 3 - Key Features and Functionalities
Speaker: Nami, Nics, and Tadz

Nami:
"Ang StackUp ay nagbibigay ng unified DevOps workspace kung saan puwedeng i-manage ang deployments, incidents, monitoring, at collaboration sa one platform lang."

Nics:
"Una, may unified deployment dashboard siya na nagta-track ng release status, environment status, rollback history, at affected services.

Pangalawa, may incident response workspace na may severity tagging, owner assignment, timelines, notes, at post-incident summaries. Helpful ito para malinaw kung sino ang gagawa at ano ang susunod na step."

Tadz:
"Kasama rin ang monitoring and observability view para makita ang logs, metrics, alerts, at system health.

May RBAC plus audit logs din para secure ang access at masubaybayan ang user actions.

Bukod doon, may team collaboration tools tulad ng mentions, updates, shared notes, at action tracking. May AI-assisted incident support din para mag-summarize ng signals at mag-suggest ng likely root cause.

At panghuli, may integrations siya sa repositories, CI/CD pipelines, at communication tools para connected pa rin sa existing workflow ng team."

## Slide 4 - Architecture Overview
Speaker: Nami and Aly

Nami:
"Sa architecture overview, makikita natin ang high-level flow ng StackUp system from browser or desktop client hanggang sa backend services."

Aly:
"Sa frontend, React at Tailwind CSS ang ginagamit para sa user interface. Tapos may API Gateway sa gitna na naka-Node.js and Express, which handles routing ng requests.

Makikita rin dito ang auth middleware with JWT verification, session tokens, at role-based permissions para secure ang access.

Sa service layer naman, hiwa-hiwalay ang deployment service, incident service, monitoring service, at user/auth service. May AI incident support module din na tumutulong sa alert summarization, anomaly detection, at root cause suggestions.

Ibig sabihin, modular ang design niya, so mas manageable, mas scalable, at mas okay for real-time operations."

## Slide 5 - Architecture Overview
Speaker: Aly and Nics

Aly:
"Ito naman ang flowchart ng request and service flow ng StackUp."

Nics:
"Nagsisimula siya kapag user nag-open ng StackUp at gumawa ng action request. Tapos dumadaan muna siya sa frontend at nagse-send ng HTTPS request papunta sa API Gateway.

Kung valid ang JWT token, chine-check muna ang role permissions like Admin, Developer, or Viewer. Kapag may 401 error, ibig sabihin hindi valid ang access.

Kapag valid naman, iroroute ng API Gateway ang request sa tamang service, whether deployment, incident, monitoring, or user/auth service.

Kung incident or alert signal ang nakita, mapupunta ito sa AI incident support module para ma-summarize ang alerts, ma-detect ang anomaly, at ma-suggest ang root cause.

After that, babalik ang response sa frontend at mag-uupdate ang dashboard in real time. Sa baba rin ng flowchart, makikita ang data at infrastructure layer na sumusuporta sa buong system."


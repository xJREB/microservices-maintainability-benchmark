# Microservices Rating Scheme

Your task is to analyze each system in this benchmark with respect to its maintainability, i.e. the degree of effectiveness and efficiency with which the system can be modified to correct, improve, extend, or adapt it. Using the [provided schema](rating-scheme.xlsx), you then have to assign five ratings per system, namely ratings for four design properties plus a holistic maintainability score.

Your ratings are based on a relative ordinal scale from `1` to `10`, where, for **all** properties, `10` is the best and `1` is the worst rating. The system that made the most convincing impression on you for a given property will receive a rating of `10` in that category. Each category therefore must have **at least one** rating of `10`. Please rate the other systems **relative** to the one you rated with the highest score.

We are also very interested in your rationale for these ratings. So for each system and property, there is also a `Comments` field that you can use to briefly document your thought process. This may be especially helpful for very good or very bad ratings, but is nonetheless optional.

## Rating Properties

- **Granularity:** The appropriateness and degree of decomposition of the system. A system with an appropriate number of evenly sized services is in general easier to understand and maintain than a system with too many fine-grained or too few coarse-grained services (whatever "appropriate", "many", and "few" may mean in the end).

- **Complexity:** The amount, variety, or difficulty of internal work carried out by the system. High complexity makes it difficult to understand the system and has a negative influence on maintainability.

- **Coupling:** The degree of  dependencies and connections between services. Systems with loosely coupled services and few inter-service dependencies are easier to maintain.

- **Cohesion:** The extent to which the operations of a service contribute towards one task or functionality. A high degree of cohesion positively impacts the maintainability of a service.

- **Overall Maintainability:** A holistic representation of the system's maintainability. You should factor in the previous properties, but you are free to include other aspects of maintainability that you deem important for Microservices. You are also free to assign weights of your judgement to all aspects. This rating can therefore be different from a simple average of the previous four properties. In such a case, we would obviously love some comments on the rationale.

## Final Remarks

- Please remember the relative nature of the benchmark! Even though the system with e.g. the "best" coupling is still mediocre compared to what you are used to, it still needs to receive a rating of `10`. All other systems then need to be placed in relation to this system.
- Please do not use sophisticated tool support to analyze the systems. You can definitely include the project in your favourite IDE to ease source code browsing, but please refrain from using static analyzers like SonarQube. The ratings should be based on your intuitive judgement and personal experience.

**Thank you very much for contributing to this research project! Happy analyzing!**
# IdentityTutorial_JulianOana
https://youtu.be/5UfJeDcoC1k

Support for ASP.NET Core Identity was added to your project.

For setup and configuration information, see https://go.microsoft.com/fwlink/?linkid=2116645.


In OAuth 2.0 terms

Principal:
   - A principal is an an entity that can be authenticated in a system and then, after authorization, assigned permissions.
   - A principal can a user, a service account, an application, or any other entity that needs to authorized so it can be securely interact with the a system.
   - A principal is an abstract representation of an entity that can be authenticated and authorized in the system. It represents the entity's identity and is associated with a set of claims.
   - In simple terms, a principal is an authenticated entity that is the subject of a security token (e.g., the user who obtained an access token after successful authentication).
   - A principal can have multiple claims associated with it. These claims contain specific information about the principal's identity and properties.
   - A principal can represent various types of entities, not just individual users. For example, a principal can be an application, a service account, or any other entity that needs to interact with the system.
   - In the context of OAuth 2.0, the principal is typically associated with the entity for which an access token is issued. The access token represents the permissions and access rights granted to that principal.

User:
   - A user is a type of principal that represents an individual who interacts with a system or application.
   - In the context of OAuth 2.0, a user typically refers to an end-user, someone who is using a client application (e.g., a mobile app, web application) to access a resource or perform an action on a resource server.
   - When an end-user logs in to a client application, the application can obtain an access token on behalf of the user through OAuth 2.0's authorization flow. This access token can then be used to access protected resources on the resource server with the user's permissions.

Claims:
   - A claim is a piece of information about an entity (usually a user) that the system can use to make authorization decisions. Claims are assertions made by an identity provider about the identity of a user. They typically consist of key-value pairs that represent attributes or properties of the user.
   - Claims can include information such as the user's name, email address, roles, permissions, group memberships, and other user-related data. Claims provide contextual information about the user's identity and the specific attributes or characteristics associated with that identity.
   - Claims are included in security tokens (e.g., JWT, SAML assertions) issued by an identity provider and are used to convey identity-related information to relying parties (e.g., applications or services) during authentication and authorization processes.
   - In an application, claims are often used to make access control decisions, personalize the user experience, and provide role-based access to different parts of the application.

Claims represent specific pieces of information about a user's identity and are included in security tokens. 
A principal, on the other hand, is an abstract entity that can be authenticated and authorized in the system and is associated with a set of claims. 
The claims associated with a principal provide contextual information about the principal's identity and attributes.
Together, claims and principals play a vital role in identity and access management systems, allowing applications to make informed authorization decisions based on the user's identity and properties conveyed through claims.

Important note: OAuth 2.0 is a protocol for authorization, not authentication. 
While it can facilitate the process of obtaining an access token on behalf of a user, it doesn't handle the actual authentication of users. 
Authentication is typically handled separately using other protocols like OpenID Connect or authentication mechanisms like username/password, multi-factor authentication, etc.
# API Title

Provide basic description of the resource. Limit to 2-3 sentences. Include verbs that indicate the supported CRUD functions - such as "Retrieve...", or if the API supports one or more CRUD functions use the verb "Manage..." 

**URI:** `/users/courses/exams` (Provide structure without values, as shown in  example)

|Basic Information ||
|:---------------- |---|
| Version  | #.# - version number plus: Alpha, Beta, General Release, or Deprecated. Unless you are versioning your API for external users, we recommend you use version 1.0 regardless of the internal versioning used for your builds.  |
| Supported Authorization Protocols  | List the supported auth protocols. Example: OAuth1, OAuth2, 3-legged OAuth, OpenID, MoAuth, etc. |
| Supported Role Types  | If applicable, list the roles supported by the API. Options are: Professor, Teaching Assistant, Student, and/or Administrator. Example: Professor and student. Delete row if not used. |

# Overview

Provide description of the resource. Include all relevant information on using this resource and the context in which it could be used.

## HTTP Verb Descriptions

| HTTP Verb 	| Description 
| :------------ |:------------- 
|`POST`			| Creates the...  
|`GET`			| Retrieves the...  
|`PUT`			| Updates the...  
|`DELETE`		| Deletes the...  

## API Routes/Parameters
List supported routes for the endpoint - such as
~~~~
/users/{userId}/courses/{courseId}/exams
/users/courses/{courseId}/exams
~~~~

### Route/Resource Parameters

Include table of parameters. Depending on the detail you need to describe you can use a simple markdown table or an HTML table. An example of each is provided here. Just delete the one you don't need.

| Name  		| Description		| Valid Values 
|:------------- |:-------------		|:-------------
|`{userId}`		| Pearson user ID.	| If no valid value, remove column 
|`{courseId}`	| Add as many rows as needed.|| 
|`{others}`		| Description | If you need to create more complex tables with multiple lines in the cells, use HTML example table provided next, and delete this markdown table.|


<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Description</th>
      <th>Valid Values</th>
  </tr>
  </thead>
  <tbody>
    <tr>
        <td><code>{userId}</code></td>
        <td>Pearson user ID.
		<p>And use HTML p (paragraph) tags to create additional paragraphs in cells.</p></td>
        <td>If multiple valid values, create a list, like this one:
           <ul>
             <li><code>value 1</code> - Returns truncated URL.</li>
             <li><code>value 1</code> - Returns full URL.</li>
           </ul></td>
    </tr>
    <tr>
        <td><code>{courseId}</code></td>
        <td>Pearson course ID.</td>
        <td></td>
    </tr>
    <tr>
        <td><code>{others}</code></td>
        <td>Add as many rows as needed.</td>
        <td></td>
    </tr>
</tbody>
</table>


## Request Header
~~~~
Request Header Body code block (include Authorization example)
~~~~

### Request Header Parameters
| Name  		| Description		|Required? 
|:------------- |:-------------		|------------- 
|`{userId}`		| Pearson user ID.	| Yes/No 
|`{others}`		| Add rows needed	| Yes/No

## Request Body
~~~~
Request Body code block, if applicable
~~~~

### Request Body Parameters

Include table of parameters. Depending on the detail you need to describe you can use a simple markdown table or an HTML table. An example of each is provided here. Just delete the one you don't need.

| Name  		| Description		| Valid Values | Required? 
|:------------- |:-------------		|:------------- |-------------
|`{userId}`		| Pearson user ID.	| If no valid value, remove column | Yes/No
|`{others}`		| Description | To create complex tables with multiple lines in the cells, use HTML example table provided next, and delete this markdown table.| Yes/No

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Description</th>
      <th>Valid Values</th>
      <th>Required?</th>
  </tr>
  </thead>
  <tbody>
    <tr>
        <td><code>{userId}</code></td>
        <td>Pearson user ID.
		<p>And use HTML p (paragraph) tags to create additional paragraphs in cells.</p></td>
        <td>If multiple valid values, create a list, like this one:
           <ul>
             <li><code>value 1</code> - Returns truncated URL.</li>
             <li><code>value 1</code> - Returns full URL.</li>
           </ul></td>
        <td>Yes/No</td>
    </tr>
    <tr>
        <td><code>{others}</code></td>
        <td>Add as many rows as needed.</td>
        <td></td>
        <td>Yes/No</td>
    </tr>
</tbody>
</table>



## Response Header
~~~~
Response Header code block, if applicable
~~~~

### Response Header Parameters

Include table of parameters. Depending on the detail you need to describe you can use a simple markdown table or an HTML table. An example of each is provided here. Just delete the one you don't need.

| Name  		| Description		|Valid Values 
|:------------- |:-------------		|:-------------
|`{userId}`		| Pearson user ID.	| If no valid value, remove column 
|`{others}`		| Description | If you need to create more complex tables with multiple lines in the cells, use HTML example table provided next, and delete this markdown table.|


<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Description</th>
      <th>Valid Values</th>
  </tr>
  </thead>
  <tbody>
    <tr>
        <td><code>{userId}</code></td>
        <td>Pearson user ID.
		<p>And use HTML p (paragraph) tags to create additional paragraphs in cells.</p></td>
        <td>If multiple valid values, create a list, like this one:
           <ul>
             <li><code>value 1</code> - Returns truncated URL.</li>
             <li><code>value 1</code> - Returns full URL.</li>
           </ul></td>
    </tr>
    <tr>
        <td><code>{others}</code></td>
        <td>Add as many rows as needed.</td>
        <td></td>
    </tr>
</tbody>
</table>


## Response Body
~~~~
Response Body code block, if applicable
~~~~

### Response Body Parameters

Include table of parameters. Depending on the detail you need to describe you can use a simple markdown table or an HTML table. An example of each is provided here. Just delete the one you don't need.

| Name  		| Description		|Valid Values 
|:------------- |:-------------		|:-------------
|`{userId}`		| Pearson user ID.	| If no valid value, remove column 
|`{others}`		| Description | If you need to create more complex tables with multiple lines in the cells, use HTML example table provided next, and delete this markdown table.|


<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Description</th>
      <th>Valid Values</th>
  </tr>
  </thead>
  <tbody>
    <tr>
        <td><code>{userId}</code></td>
        <td>Pearson user ID.
		<p>And use HTML p (paragraph) tags to create additional paragraphs in cells.</p></td>
        <td>If multiple valid values, create a list, like this one:
           <ul>
             <li><code>value 1</code> - Returns truncated URL.</li>
             <li><code>value 1</code> - Returns full URL.</li>
           </ul></td>
    </tr>
    <tr>
        <td><code>{courseId}</code></td>
        <td>Pearson course ID.</td>
        <td></td>
    </tr>
    <tr>
        <td><code>{others}</code></td>
        <td>Add as many rows as needed.</td>
        <td></td>
    </tr>
</tbody>
</table>


## Response HTTP Codes

Either link to single document that lists response codes or all related APIs, or create table of error codes here.

| HTTP Status Code and Message	| Description			
|:------------------------------|:----------------------
| `200 OK`						| Request successful
| `400 Bad Request`				| Request had incorrect syntax (badly formed) or was missing a required field during a `POST` or `PUT`.
| `add rows`					| and descriptions as needed



## Examples

Add as many examples as needed (at least one for each CRUD function).

### Example 1

#### Request
~~~~
Request code block
~~~~

#### Response
~~~~
Response code block
~~~~

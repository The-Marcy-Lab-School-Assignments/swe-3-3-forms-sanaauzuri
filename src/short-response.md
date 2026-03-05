# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: Accessibility

What is accessibility and why does it matter? Name at least two ways that labels make our form inputs more accessible?

**Your Answer:**

Acessibility means ensuring that everyone can use something, regardless of disabilities or impairments.  This matters because no one should be barred/left out from using a website or app because of their abilities.  Labels help with accessibility in two ways: the `for` attribute connects the label to its input so screen readers can tell the user what the input is for. Secondly, clicking a label automatically clicks its input, making the form easier to use for everyone.

## Question 2: The `name` vs `id` Attribute

`for`, `name` and `id` are attributes we put on form labels and inputs, but they serve different purposes. Explain what each attribute is used for.

**Your Answer:**

`for`: The `for` attribute on a label connects to a matching `id` attribute on `<input>` so screen readers can tell which label belongs to which field.\
`name`: The `name` attribute labels the data when a form is submitted. For example, `name="email"` tells the server that the submitted value is the user's email.\
`id`: The `id` attribute gives an element a unique id so it can either be connected to a label, or styled with CSS.

## Question 3: Input Types

Why do we use specific input types like `type="email"` or `type="number"` instead of just using `type="text"` for everything? What advantages do they provide?

**Your Answer:**

We use specific input `type` attributes to specify what the input will accept. For example, `type="email"` checks that the user enters a valid email format, and `type="number"` only allows numbers. This gives us more control over the form and stops user from submitting incorrect information.

## Question 4: Form Submission

Form data is typically sent to a server (a computer that receives the data and does something with it). Provide an example of a real web application that uses a form and, to the best of your ability, explain what the application does with that form data.

**Your Answer:**

Google uses a sign-in form that asks for an email address and password. When the user submits the form, that data is sent to Google's servers, which check it compared to stored account information. If it matches, the user is logged in and given access to their account.
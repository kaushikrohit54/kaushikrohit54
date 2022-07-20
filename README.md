GraphqlAPI for Contact form



`mutation {
  createContact(
    input: {
      name: "Rohit kaushik"
      mobile: "9711154754"
      email: "kaushikrohit54@gmail.com"
      feedback: "This is my feedback or query to rohit kaushik"
      disclaimer: "Yes"
    }
  )
  {
    feedback_submit {
      entity_id
      name
      mobile
      email
      feedback
      disclaimer
    }
  }
}`

  

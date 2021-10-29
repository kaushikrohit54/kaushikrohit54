GraphqlAPI for custom feedback form



`mutation {
  createQueryFeedbacks(
    input: {
      name: "Rohit kaushik"
      mobile: "9711154754"
      email: "rohit.kaushik@publicisgroupe.com"
      feedback: "This is my feedback or query to admin"
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

  

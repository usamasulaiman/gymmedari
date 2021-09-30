<script>
  const questionsList = [
    {
      id:2,
      question: 'what colour is a banana',
      answer: 'yellow',
    },
    {
      id:2,
      question: 'when should you eat',
      answer: 'all the time',
    },
  ]
</script>

<table class="container questions-list">
  <thead>
    <tr>
      <th>Question</th>
      <th>Answer</th>
    </tr>
  </thead>
  <tbody>
    {#each questionsList as questionItem, i}
      <tr>
        <td>{questionItem.question}</td>
        <td>{questionItem.answer}</td>
      </tr>
    {/each}
  </tbody>
</table>

<style>
  .questions-list {
    margin-top: 50px;
    border: 1px solid;
    border-radius: 4px;
    padding: 10px;
  }
  .questions-list tr {
    height: 28px;
  }
  .questions-list tr:nth-child(2) {
    background: wheat;
  }
</style>
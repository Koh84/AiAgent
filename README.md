# AiAgent

pip install asana 
pip install openai
pip install python-dotenv


# Simulate the tool call response

response = {
  "choices": [
      {
          "message": {
              "role": "assistant",
              "tool_calls": [
                  {
                      "id": "call_62136354",
                      "type": "function",
                      "function": {
                          "arguments": "{'order_id': 'order_12345'}",
                          "name": "get_delivery_date"
                      }
                  }
              ]
          }
      }
  ]
}


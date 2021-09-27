- const postToDialogflow = req => {
  req.headers.host = "dialogflow.cloud.google.com";
  return request.post({
    uri: "https://dialogflow.cloud.google.com/v1/integrations/line/webhook/3d4f3b90-c4ee-4950-bf6c-3fe915efe722
    headers: req.headers,
    body: JSON.stringify(req.body)
  });
};

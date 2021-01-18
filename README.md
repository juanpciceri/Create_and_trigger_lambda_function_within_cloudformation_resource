# Create_and_trigger_lambda_function_within_cloudformation_resource
Sometimes you need to create a lambda function with cloudformation and trigger it, inmediately after created. With this cloudformation custom resource and python commands you may do that task.

Because you need to let know to AWS cloudformation that lambda was already triggered to continue with the creation of the following resources, you must use "cfn" library. This library from my experience is only in used with python 2.7. Pls. be aware of that.

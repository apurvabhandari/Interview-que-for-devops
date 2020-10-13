How would you define the cidr_block for us-east-1 in the aws_vpc resource using a variable?

✅ Correct: var.vpc_cidrs[“us-east-1”]
❌ Incorrect: var.vpc_cidrs.0
❌ Incorrect: vpc_cidrs[“us-east-1”]
❌ Incorrect: var.vpc_cidrs[0]

You have defined the values for your variables in the file terraform.tfvars, and saved it in the same directory as your Terraform configuration. Which of the following commands will use those values when creating an execution plan?

❌ Incorrect: terraform plan
❌ Incorrect: terraform plan -var-file=terraform.tfvars
✅ Correct: All of the above
❌ Incorrect: None of the above

»Multiple Answer
Multiple answer questions ask you to identify multiple correct answers from a list. We will always tell you how many correct answers you can expect to find, if there's more than one.

»Examples
Which of the following Terraform commands will automatically refresh the state unless supplied with additional flags or arguments? Choose TWO correct answers.

✅ Correct: terraform plan
❌ Incorrect: terraform state
✅ Correct: terraform apply
❌ Incorrect: terraform validate
❌ Incorrect: terraform output

What happens when you apply Terraform configuration? Choose TWO correct answers.

✅ Correct: Terraform makes any infrastructure changes defined in your configuration.
❌ Incorrect: Terraform gets the plugins that the configuration requires.
✅ Correct: Terraform updates the state file with any configuration changes it made.
❌ Incorrect: Terraform corrects formatting errors in your configuration.
❌ Incorrect: Terraform destroys and recreates all your infrastructure from scratch.

»Text Match
Text match questions present you with a statement and ask you to fill in the blank by typing an answer into a text box. Because we know that you could make a typo, in addition to the technically correct answer, we'll also accept variations of the answer that still demonstrate your understanding of the material. Text match is not case sensitive.

»Example
Which flag is used to find more information about a Terraform command? For example, you need additional information about how to use the plan command. You would type: terraform plan _____. Type your answer in the field provided. The text field is not case-sensitive and all variations of the correct answer are accepted.

✅ -h
✅ -help
✅ --help

Answers that would also receive full credit:

--h
terraform plan -h
terraform plan --h
terraform plan -help
terraform plan --help
terraform -h plan
terraform -help plan
terraform --help plan
plan -h
plan --h
plan -help
plan --help
-h plan
-help plan
--help plan

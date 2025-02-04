
# Welcome to your CDK Python project!

This is a blank project for CDK development with Python.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

This project is set up like a standard Python project.  The initialization
process also creates a virtualenv within this project, stored under the `.venv`
directory.  To create the virtualenv it assumes that there is a `python3`
(or `python` for Windows) executable in your path with access to the `venv`
package. If for any reason the automatic creation of the virtualenv fails,
you can create the virtualenv manually.

To manually create a virtualenv on MacOS and Linux:

```
$ python3 -m venv .venv
```

After the init process completes and the virtualenv is created, you can use the following
step to activate your virtualenv.

```
$ source .venv/bin/activate
```

If you are a Windows platform, you would activate the virtualenv like this:

```
% .venv\Scripts\activate.bat
```

Once the virtualenv is activated, you can install the required dependencies.

```
$ pip install -r requirements.txt
```

At this point you can now synthesize the CloudFormation template for this code.

```
$ cdk synth
```

To add additional dependencies, for example other CDK libraries, just add
them to your `setup.py` file and rerun the `pip install -r requirements.txt`
command.

## Useful commands

 * `cdk ls`          list all stacks in the app
 * `cdk synth`       emits the synthesized CloudFormation template
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk docs`        open CDK documentation

Enjoy!

## References

 * [(AWS Machine Learning Blog) Unlock cost savings with the new scale down to zero feature in SageMaker Inference (2024-12-02)](https://aws.amazon.com/blogs/machine-learning/unlock-cost-savings-with-the-new-scale-down-to-zero-feature-in-amazon-sagemaker-inference/)
 * [(GitHub) sagemaker-genai-hosting-examples](https://github.com/aws-samples/sagemaker-genai-hosting-examples) - see `scale-to-zero-endpoint`
* [Amazon EC2 Instance types](https://aws.amazon.com/ec2/instance-types/)
* Unlock Cost Savings with New Scale-to-Zero Feature in SageMaker Inference
* https://github.com/aws-samples/sagemaker-genai-hosting-examples/blob/main/scale-to-zero-endpoint/llama3-8b-scale-to-zero-autoscaling.ipynb
* Deploy DeepSeek R1 Large Language Model from HuggingFace Hub on Amazon SageMaker
* https://github.com/aws-samples/sagemaker-genai-hosting-examples/blob/main/Deepseek/DeepSeek-R1-Llama8B-LMI-TGI-Deploy.ipynb
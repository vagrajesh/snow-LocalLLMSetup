# snow-LocalLLMSetup
PART 1: Create New System Properties
Navigation
Navigator → Type: "sys_properties.list"
Press Enter → Click "New" for each


PART 2: Create the New Script Include
Navigation
Navigator → Type: "Script Includes"
Navigate to: System Definition → Script Includes
Click "New"
Configuration
Field	Value
Name	AITestCaseGenerator
API Name	AITestCaseGenerator (auto-fills)
Client callable	❌ Unchecked
Active	✅ Checked
Description	Provider-agnostic AI test case generator (supports cloud and local LLM providers)


COMPONENT 1: TestManagementUtils
Navigation
Navigator → Type: "Script Includes"
Navigate to: System Definition → Script Includes
Click "New" (or open existing "TestManagementUtils" if it already exists)
Configuration
Field	Value
Name	TestManagementUtils
API Name	TestManagementUtils (auto-fills)
Client callable	✅ Checked
Active	✅ Checked
Description	Utility methods for creating tests, versions, steps, and M2M story linkage in Test Management 2.0

COMPONENT 2: UI Action — "Generate AI Test Cases"
Navigation
Navigator → Type: "System UI"
Navigate to: System UI → UI Actions
Click "New" (or open existing "Generate AI Test Cases" if it exists)
Configuration
Field	Value
Name	Generate AI Test Cases
Table	rm_story
Action name	generate_ai_test_cases
Active	✅ Checked
Show insert	❌ Unchecked
Show update	✅ Checked
Form button	✅ Checked
Form context menu	❌ Unchecked
List banner button	❌ Unchecked
List choice	❌ Unchecked
List context menu	❌ Unchecked
Client	❌ Unchecked (Server-side)
Order	100


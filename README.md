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


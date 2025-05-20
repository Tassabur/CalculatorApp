# CalculatorApp
CalculatorApp using jetpack compose 

*UI Composables Usedas shown below:

Column: Arranges UI vertically – used for layout of main screen and buttons

Row:Arranges buttons in rows


Box:Container used for expression/result display with scroll

Text:Shows expressions and results

TextButton:Used for "⌫" and "C" (Clear) buttons

Button:Used for calculator number and operation buttons

Spacer:Adds spacing between elements

Modifier:Modifies layout (e.g. padding, fillMaxWidth, weight, aspectRatio, etc.)

MaterialTheme.colorScheme	Used for theming text color

remember { mutableStateOf(...) }:Stores and updates expression and result

LaunchedEffect(expression):Reactively evaluates expression when it changes

rememberScrollState():Provides a scroll state for vertical scrolling

verticalScroll(scrollState):Enables vertical scrolling on a Box or Column
heightIn(min, max)	Restricts the height of the scrollable area

*Theme and App Structure: as shown below

CalculatorAppTheme:Wraps your content with a custom Material theme

ComponentActivity + setContent	Sets Compose UI content in MainActivity

*Expression Evaluator:

You also implemented a custom mathematical expression parser using Kotlin standard syntax (not Compose specific), with:

Custom recursive parsing logic

Support for +, -, *, /, %, (), and unary operators







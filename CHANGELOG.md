* 1.7.4

	+ `LineRendererCamera` now needs explicit material (to work on device)
	+ `ExecutionOrders` runs only in Editor

* 1.7.3

	+ Centroid calculations
		+ `Polygon.centroid`
		+ `Geometry.CentroidOfPolygons`

* 1.7.2

	+ `EPPZ.ExecutionOrder`
		+ Added `ExecutionOrder` attribute to Mono classes
	+ `EPPZ.Lines`
		+ Arranged execution order (`LineRendererCamera` first, then all the `LineRendererBase` instances)

* 1.7.1

	+ `EPPZ.Lines`
		+ Not collected upfront, but on instance creation
		+ `DrawPoints` can be open ended

* 1.7.0

	+ `NGUI/Scroll View Page Control` now uses 2D colliders

* 1.6.9

	+ `PolygonSource` can have `offset`

* 1.6.8

	+ Added `Triangle.Net`
		+ Along releated `EPPZ.Geometry` / `Polygon` extensions

* 1.6.7

	+ Mostly refactoring

* 1.6.6

	+ `EPPZ.Lines`
		+ Removed `EPPZ.Geometry` dependencies

* 1.6.5

	+ `EPPZ.Lines`
		+ Removed unnecessary transparent lines

* 1.6.4

	+ `EPPZ.Lines`
		+ Inactive when component disabled

* 1.6.3

	+ `EPPZ.Lines`
		+ Circle drawing moved into

* 1.6.2

	+ `EPPZ.Lines`
		+ Example scenes

* 1.6.1

	+ `EPPZ.Lines`
		+ Removed 2D restriction from `EPPZ.Lines.Line`

* 1.6.0

	+ `EPPZ.Lines`
		+ Some naming
		+ Added `CachedLineRenderer` (behaves almost like `UnityEngine.LineRenderer`)

* 1.5.9

	+ `DebugRenderer` refactor
		+ Namespace to `EPPZ.Lines`
		+ Renamed to `LineRenderer` (which is actually does)
		+ More batching (collect each line)

* 1.5.8

	+ `DebugRenderer` refactor
		+ Single drawcall
		+ Using colors intead materials
		+ Shader using vertex color

* 1.5.7

	+ Encapsulated folder structure
		+ `Editor`, `Scenes` are all package contained

* 1.5.6

	+ Naming (with automatic scene / prefab updates)
		+ `Geometry`

* 1.5.5

	+ Naming (with automatic scene / prefab updates)
		+ `NGUI`
		+ `Editor`

* 1.5.4

	+ Namings (with automatic scene / prefab updates)
		+ `EditorUtils`
		+ `Extensions`
		+ `UI`
		+ `Utils`

* 1.5.3

	+ Namings (with scene / prefab updates)
		+ `EPPZMesh.EPPZ_CircleMesh2D` to `EPPZ.Meshes.CicleMesh`
		+ `EPPZMesh.EPPZ_RingMesh2D` to `EPPZ.Meshes.RingMesh`

* 1.5.2

	+ Namings
		+ `EPPZDebug.EPPZ_DebugCamera` to `EPPZ.DebugTools.DebugCamera`
		+ `EPPZDebug.EPPZ_DebugCamera` to `EPPZ.DebugTools.DebugCamera`
		+ `EPPZDebug.EPPZ_DebugRenderer` to `EPPZ.DebugTools.DebugRenderer`
		+ `EPPZDebug.EPPZDebug_CornerDebugRenderer` to `EPPZ.DebugTools.CornerDebugRenderer`
		+ `EPPZDebug.EPPZDebug_PolygonDebugRendrer` to `EPPZ.DebugTools.PolygonDebugRenderer`
		+ `EPPZDebug.EPPZDebug_SegmentDebugRenderer` to `EPPZ.DebugTools.SegmentDebugRenderer`
		+ With corresponding Script reference updates in scenes / prefabs

* 1.5.1

	+ Namings
		+ Containing folder to `Assets/eppz!`

* 1.5.0

	+ `EPPZNGUI_ScrollViewPageControl` fixes

* 1.4.9

	+ Some `null` check

* 1.4.8

	+ Tracing utils uses NGUI labels

* 1.4.7

	+ `EPPZNGUI_ScrollViewPageControl` fixes

* 1.4.6

	+ `EPPZNGUI_ScrollViewPaging`
		+ Delegate hooks

* 1.4.5

	+ `EPPZKit_String`

* 1.4.2 - 1.4.4

	+ `EPPZNGUI_ScrollViewPageControl`

* 1.4.1

	+ `EPPZNGUI_DragPerpendicularScrollViews`

* 1.3.8 - 1.4.0

	+ `EPPZNGUI_ScrollViewPaging` fixes

* 1.3.7

	+ `EPPZNGUI_ScrollViewPaging`

* 1.3.6

	+ `EPPZNGUI_UICenterOnChild`

* 1.3.4 - 1.3.5

	+ `EPPZNGUI_AnchorSizeConstraint`	
	+ `EPPZNGUI_AspectRulesConstraint`

* 1.2.9 - 1.3.3

	+ Dense refactor / tests

* 1.2.8

	+ `EPPZNGUI_PositionConstraint`	

* 1.2.7

	+ `EPPZNGUI_AspectConstraint`	
	+ Serialization
	+ Delegate management on Play / Edit mode switches

* 1.2.6

	+ `EPPZNGUI_SizeConstraint`	
	+ Delegate inspector

* 1.2.5

	+ `EPPZNGUI_SizeConstraint`

* 1.2.4

	+ `EPPZNGUI_SizeConstraint`

* 1.2.3

	+ `EPPZUI_PositionConstraint`

* 1.2.2

	+ `EPPZEditor_SliceRenamer`
		+ Lovely embedded header images right in the single script file

* 1.2.1

	+ `EPPZEditor_SliceRenamer`
	+ `EPPZEditor_HandTool`
		+ Typo

* 1.2.0

	+ `EPPZGeometry_Polygon`
		+ Some topology feature
			+ `AlignCentered`
			+ `Scale`
			+ `Translate`
			+ `RecalculateWindingDirection`		

* 1.1.9

	+ `EPPZGeometry_Polygon`
		+ Polygon enumerator (mainly for TriangleNet connections)

* 1.1.8

	+ Utils
		+ Refactored tools to utils (class naming and namespace)
		+ `EPPZUtils_FPSLabel`

* 1.1.7

	+ `EPPZUI_ScrollRect`
		+ Added `snapDistance` (expressed in page size percentage) for easier paging UX
		+ Perpendicuar `EPPZUI_ScrollRect` also flicking (dispatch initial touch data as well)
		+ Refactor (marged types, naming)

* 1.1.6

	+ `EPPZUI_ScrollRect`
		+ Paging (both horizontal and vertical)
		+ Flick gesture (to page for a brief drag)

* 1.1.5

	+ `EPPZUI_ScrollRect`
		+ Removed dependency on interactable content on ScrollRect
		+ Perpendicular ScrollRect lookup now traverses hierarchy only (removed raycast based implementation)

* 1.1.4

	+ `EPPZUI_ScrollRect`
		+ A lovely class that resolves perpendicular ScrollRect issue
			+ A vertical ScrollRect now won't block a horizontal ScrollRect from scrolling 
			+ Same behaviour as embedded UIScrollView in iOS

* 1.1.2

	+ `EPPZUI_AspectConstraint`
		+ Bind Rect Transform aspect together along customizable rules
	+ EPPZUI_CellSizeConstraint`
		+ `GridLayoutGroup` extension to control cell size with reference `rectTransform`

* 1.1.1

	+ `EPPZUI_SizeConstraint`
		+ Bind Rect Transform values together (updates in editor as well)

* 1.1.0

	+ `EPPZEditor_HandTool`
		+ Hold space for pan
	+ `EPPZTools_ActivateOnAwake` 
		+ As it goes
	+ `EPPZTools_RetinaCanvas`
		+ Sets UI scale to 2 on retina (high DPI) devices
	+ `EPPZUI_Draggable`
		+ Draggable panel with top / bottom snapping
		+ Base solution for paging scroll

* 1.0.1 - 1.0.2 (00:00)

	+ `Polygon` fixes
		+ Calculate winding number before area calculation on construction
		+ `polygonCount` introduced
		+ `count` properties public

* 1.0.0 (00:10)

	+ Flip normals of clipper paths (reverse enumeration)
	+ Removed legacy offset algorithm
	+ Removed `IntersectionVertex` and its debugger

* 0.3.1 (00:20)

	+ Added multi-polygon support

* 0.3.0 (00:50)

	+ Hooked in Clipper library for offsetting

* 0.2.8 (01:10)

	+ Offset polygon cleanup refactor
		+ Only works (tested) with non-polygonal loops

* 0.2.7 (01:30)

	+ Attempts to debug offset polygon cleaning
		+ Ended up with a clickable enumerator architecture
		+ Still broken, but debuggable!

* 0.2.6 (00:40)

	+ Polygon inspector
		+ Debug tool for inspecting edge graph of polygon
	+ `Polygon`
		+ Offset polygon cleaning fixes

* 0.2.5 - 0.2.51 (01:20)

	+ Cleaning up offset polygon
		+ Collection, pooling just fine
		+ Works fine without loop polygons
		+ Testbed shows both raw and cleaned up polygon
	+ `IntersectionVertex`
		+ Evaluated to be equal when edges are the same (no distance check)

* 0.2.4 (00:10)

	+ `Segment`
		+ Implement `Segment` intersection point without (!) accuracy
		+ Updated test scene
			+ `TestScene_08_Controller`

* 0.2.3 - 0.2.35 (01:00)

	+ `Polygon`
		+ `CalculateAreaRecursive()`
			+ Area calcuations can consider sub-polygons (based on facing)
		+ Winding test still local
		+ Debug Renderer can now draw edge normals (!)
	+ Updating test scenes for multi-polygon	
		+ `07 Polygon area, winding direction`

* 0.2.2 (01:00)

	+ `Polygon`
		+ Look for sub polygons in `EPPZGeometry_PolygonSource` objects
		+ Create bus polygons recursively
		+ `EPPZ_DebugRenderer.DrawPolygon()` updated using edge enumerator
		+ `IsIntersectingWithSegment` now recursive
		+ `PermiterContainsPoint` now recursive
	+ Updating test scenes for multi-polygon
		+ `TestScene_00_Controller`
		+ `TestScene_01_Controller`
		+ `TestScene_02_Controller` (stayed simple)
		+ `TestScene_03_Controller`
		+ `TestScene_04_Controller` (updated references only)
		+ `TestScene_05_Controller`
		+ `TestScene_051_Controller`
			+ Permiter containment is actually useless test here
		+ `TestScene_052_Controller`
		+ `TestScene_06_Controller` (unchanged actually)


* 0.2.1 (02:40)

	+ `Polygon`
		+ New Polygon constructor with optional winding direction inputs
		+ Removed index magic accessors
			+ PointForIndex(int index);
			+ public Vector2 NextPointForIndex(int index);
			+ public Vector2 PreviousPointForIndex(int index);
			+ public Vertex VertexForIndex(int index);
			+ public Vertex NextVertexForIndex(int index);
			+ public Vertex PreviousVertexForIndex(int index)
			+ Using enumerators instead
		+ `bounds` / `area` are recursive
			+ `CalculateBounds()` uses `EnuemratePointsRecursive()`
			+ `CalculateArea()` adds up sub-polyons as well
	+ `Vertex`
		+ `previousVertex` / `nextVertex`
			+ Gets injected at creation time
		+ `previousEdge` / `nextEdge`
			+ Gets injected at creation time
		+ `edge`
			+ Removed
	+ Test scenes works well

* 0.2.0 (01:00)

	+ `Polygon`
		+ Sub polygon store
		+ Recursive enumerators
		+ Recursive point counter (for triangulating)
		+ pointCount / vertexCount / edgeCount gone private

* 0.1.9 (00:30)

	+ EPPZGeometry refactor (namings / method order)
	+ Outlined sub-polygon behaviour

* 0.1.8 (00:40)

	+ Start collecting `Edge.b` points
	+ Loop mode outlined, needs to be more recursive
		+ Something like, "Pool points here until this point"
		+ `IntersectionVertex` implements `IEquatable`

* 0.1.7 (02:20)

	+ Polygon offset algorithm
		+ Fixed `Edge.nextEdge` calculations
		+ Loop polygon tests implemented
		+ Fixed `IntersectionVertex.CalculateIntersection` calculations
		+ Test scene
			+ Created intersection vertex renderers (really custom only for this)
			+ Intersection vertices can be inspected

* 0.1.6 (01:00)

	+ Intersection point and intersection test has merged
		+ Uses `Physics.Raycast` API style (bool return, output parameter as result)
		+ Can use accuracy, containment method
		+ Some documentation

* 0.1.54

	+ Replaced intersection algorithm

* 0.1.53

	+ Implemented `08 Segment-segment intersection point` test scene
	+ Hooked in segment intersection algorithm to `Geometry`

* 0.1.52

	+ Created `08 Segment-segment intersection point` test scene

* 0.1.51

	+ GitHub deploy
	+ Detached version control from tangram! project included as a submodule

* 0.1.5

	+ Fixed `08 Polygon offset` test scene
	+ Scoping

* 0.1.4

	+ Polygon offset extracted
		+ `Edge`
			+ `perpendicular` / `normal` calculations
			+ Automatic calculation can be managed by `alwaysCalculate`
		+ `Vertex`
			+ `bisector` / `normal` calculations
			+ Automatic calculation can be managed by `alwaysCalculate`
			+ `nextEdge` fix
		+ `Polygon.OffsetPolygon()` added
		+ `08 Polygon offset` test scene
	+ `EPPZGeometry_PolygonDebugRenderer`
		+ `Polygon` model can be sourced from outside

* 0.1.3

	+ Area / Winding Direction calculations
		+ Calculate signed area first, assign winding direction, then area
		+ Calculation results are read-only properties
			+ `bounds`
			+ `signedArea`										
			+ `area`		
			+ `windingDirection`
		+ Corresponding test scene added

* 0.1.2

	+ Test scene / documentation improvements
	+ Debug renderes now works in Scene View as well
	+ Polygon winding direction can be `Unknown` by default

* 0.1.1

	+ `Segment.IsPointLeft()` added with testbed

* 0.1.0

	+ `Segment` / `Edge` relationship
		+ Segment.a / Segment.b accessors made virtual
		+ Subclasses can override so `Edge` now sources `Polygon` points directly 
	+ Test scenes comply

* 0.0.9

	+ `Edge` / `Vertex` classes
		+ Seemingly `Edge` instances can't reach `Vector2` sources this way
		+ Bounding / inheritance should clean up

* 0.0.8

	+ Pass `EPPZPolygon_2` test scene

* 0.0.7 - 0.0.8

	+ Integrate permiter containment test into `Polygon`

* 0.0.5 - 0.0.6

	+ Segment point containment test
	+ Bounds Containment (with equality) is fixed
	+ Bounds Rect is converted to world coordinate system (Y-up)
	+ `Segment.IsSegmentIntersecting` uses `Rect.Overlaps` test for optimization (again)

* 0.0.4

	+ More testbed scenes with selectable test algorithms

* 0.0.3

	+ `EPPZPolygon` Test scene
		+ Test `Segment.IsIntersectingWithSegment`
		+ Test `PolygonIsIntersectingWithSegment`
	+ Fixed bounds overlap test
	+ Debug renderers
		+ Draw bounds as well
		+ Works with identy (zero) source transforms (!)

* 0.0.2

	+ `EPPZ_PolygonSource` / `EPPZ_SegmentSource`
		+ sources now carry a model instance
		+ can be updated runtime
	+ Test scenes
		+ `EPPZMesh`
		+ `EPPZPolygon`

* 0.0.1

	+ Naming
	+ Extracted `EPPZ_DebugRenderer`
		+ Coupled with `EPPZ_DebugCamera
	+ `EPPZGeometry`		
		+ Moved `Vector2` / `Vector3` extensions into 
		+ Still contains `Polygon` / `Segment` / `Point`
		+ Moved polygon source into
	+ `EPPZMesh` with ring and circle 2D
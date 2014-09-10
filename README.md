STRUCTURAL ANALYSIS VIEW
=====================================================


Overview and Documents
=====================================================

- see directory Descriptions --> StructuralAnalysisView_Overview.jpg (jpg has built in Preview in github!)

- Net: http://www.buildingsmart-tech.org/specifications/ifc-view-definition/structural-analysis-view



IfcStructuralMember
=====================================================

- Net: http://www.buildingsmart-tech.org/ifc/IFC2x4/beta1/html/ifcstructuralanalysisdomain/lexical/ifcstructuralmember.htm

_ ABSTRACT SUPERTYPE OF   (ONEOF(IfcStructuralCurveMember, IfcStructuralSurfaceMember)) 



IfcStructuralCurveMember
-----------------------------------------------------
- Net: http://www.buildingsmart-tech.org/ifc/IFC2x4/beta1/html/ifcstructuralanalysisdomain/lexical/ifcstructuralcurvemember.htm


- Definition from IAI: Instances of IfcStructuralCurveMember describe edge members, i.e. structural analysis idealizations of beams, columns, rods, etc. Curve members may be straight or curved.
  
- Topology Use Definitions:
  Direct instances of IfcStructuralCurveMember shall have a topology representation which consists of one instance of IfcEdge or a subtype, representing the reference curve of the curve member. See definitions at IfcStructuralItem for further specifications.


IfcStructuralSurfaceMember
-----------------------------------------------------
- Net: http://www.buildingsmart-tech.org/ifc/IFC2x4/beta1/html/ifcstructuralanalysisdomain/lexical/ifcstructuralsurfacemember.htm

- Definition from IAI: Instances of IfcStructuralSurfaceMember describe face members, i.e. structural analysis idealizations
  of slabs, walls, shells, etc. Surface members may be planar or curved.

- Topology Use Definitions: Direct instances of IfcStructuralSurfaceMember shall have a topology representation 
  which consists of one IfcFaceSurface, representing the reference surface of the surface member. 
  See definitions at IfcStructuralItem for further specifications.


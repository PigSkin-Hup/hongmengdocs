# pms\_types.h<a name="EN-US_TOPIC_0000001055678070"></a>

-   [Overview](#section1906041262165628)
-   [Summary](#section1277663167165628)
-   [Data Structures](#nested-classes)
-   [Macros](#define-members)
-   [Enumerations](#enum-members)

## **Overview**<a name="section1906041262165628"></a>

**Related Modules:**

[Pms\_types](pms_types.md)

**Description:**

Declares variables and data structures used by the permission management module. 

To use permission management APIs, you must obtain this file.

**Since:**

1.0

**Version:**

1.0

## **Summary**<a name="section1277663167165628"></a>

## Data Structures<a name="nested-classes"></a>

<a name="table1145650333165628"></a>
<table><thead align="left"><tr id="row1734014016165628"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p116554713165628"><a name="p116554713165628"></a><a name="p116554713165628"></a>Data Structure Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1672975934165628"><a name="p1672975934165628"></a><a name="p1672975934165628"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row112538238165628"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1598946282165628"><a name="p1598946282165628"></a><a name="p1598946282165628"></a><a href="permissionsaved.md">PermissionSaved</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p30546811165628"><a name="p30546811165628"></a><a name="p30546811165628"></a>Defines the permission, including the name, description, and whether the permission is granted. </p>
</td>
</tr>
</tbody>
</table>

## Macros<a name="define-members"></a>

<a name="table776088297165628"></a>
<table><thead align="left"><tr id="row1984065244165628"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p549485261165628"><a name="p549485261165628"></a><a name="p549485261165628"></a>Macro Name and Value</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p534295146165628"><a name="p534295146165628"></a><a name="p534295146165628"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1422524887165628"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1607283078165628"><a name="p1607283078165628"></a><a name="p1607283078165628"></a><a href="pms_types.md#ga1d7d82a3741ecedc4d993b523d95c0c8">PERM_NAME_LEN</a>   64</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1643883086165628"><a name="p1643883086165628"></a><a name="p1643883086165628"></a>Indicates the length of a permission name. </p>
</td>
</tr>
<tr id="row1153620354165628"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p711475107165628"><a name="p711475107165628"></a><a name="p711475107165628"></a><a href="pms_types.md#gafb859b51e2b9552103cf1ba665e8eb7a">PERM_DESC_LEN</a>   128</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1844957971165628"><a name="p1844957971165628"></a><a name="p1844957971165628"></a>Indicates the length of a permission description. </p>
</td>
</tr>
</tbody>
</table>

## Enumerations<a name="enum-members"></a>

<a name="table1860127774165628"></a>
<table><thead align="left"><tr id="row1794342785165628"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p1345304149165628"><a name="p1345304149165628"></a><a name="p1345304149165628"></a>Enumeration Name</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p1331664924165628"><a name="p1331664924165628"></a><a name="p1331664924165628"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1621402884165628"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1231608907165628"><a name="p1231608907165628"></a><a name="p1231608907165628"></a><a href="pms_types.md#ga56644f429963f015addb12e36e2344f7">IsGranted</a> { <a href="pms_types.md#gga56644f429963f015addb12e36e2344f7a3d1fb18b35633f486c86113d8ed298b0">NOT_GRANTED</a> = 0, <a href="pms_types.md#gga56644f429963f015addb12e36e2344f7a440c8b08fdd77c2aa90283c06dbe465a">GRANTED</a> = 1 }</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1851166974165628"><a name="p1851166974165628"></a><a name="p1851166974165628"></a>Enumerates granting statuses of the permission. </p>
</td>
</tr>
<tr id="row1907243361165628"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p204221988165628"><a name="p204221988165628"></a><a name="p204221988165628"></a><a href="pms_types.md#gacb79d7f5cd64c73479e0bdd9525265a8">PmsErrorCode</a> {   <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8a0c588903ef5651fc0305f212e093c492">PERM_ERRORCODE_SUCCESS</a> = 0, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8ad3d70d0327fc60a9067f853bbe938fd4">PERM_ERRORCODE_INVALID_PARAMS</a> = 10, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8ae6c8da1f46cf729021be0ee3ac28d506">PERM_ERRORCODE_INVALID_PERMNAME</a>, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8a29ad932e0c9f71f287b0854635fbfdfc">PERM_ERRORCODE_MALLOC_FAIL</a>,   <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8a93548eedb6a47d5240f04d9e7066ae42">PERM_ERRORCODE_OPENFD_FAIL</a>, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8ad5bbbd7a5c1964a8e32f8cd910d1e1b1">PERM_ERRORCODE_READFD_FAIL</a>, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8ac9f97daf3819939bec448a74633d76dd">PERM_ERRORCODE_WRITEFD_FAIL</a>, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8a93871916c514e5e08b5e71668e78c5f9">PERM_ERRORCODE_JSONPARSE_FAIL</a>,   <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8a21d2c3ca74a60578d909d7e3599d2329">PERM_ERRORCODE_COPY_ERROR</a>, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8ab60b867e2cd8d6dad65fec5438bc9d8f">PERM_ERRORCODE_FIELD_TOO_LONG</a>, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8ae50528fd433961afa3d384a296d7c1e1">PERM_ERRORCODE_PERM_NOT_EXIST</a>, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8aee363de3178fe3be3d48c6b93a9ab0e2">PERM_ERRORCODE_UNLINK_ERROR</a>,   <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8a09f77eaf46086239b3e72abfe8629d6d">PERM_ERRORCODE_FILE_NOT_EXIST</a>, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8a2041efbb9d8c5dd30df4894ee7cc7b1e">PERM_ERRORCODE_MEMSET_FAIL</a>, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8a62c441a20ff74358ff3400a60d11d2a2">PERM_ERRORCODE_STAT_FAIL</a>, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8ae652b4433e08622981c7457b4ead9dd8">PERM_ERRORCODE_PATH_INVALID</a>,   <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8a28397170788e73451c03bdacaf07bb09">PERM_ERRORCODE_TOO_MUCH_PERM</a>, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8a20ce1cb092907845a84f138e45d06651">PERM_ERRORCODE_TASKID_NOT_EXIST</a>, <a href="pms_types.md#ggacb79d7f5cd64c73479e0bdd9525265a8a2e7d34ab9f33c396cac29e094277fef5">PERM_ERRORCODE_PERM_NUM_ERROR</a> }</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1651507550165628"><a name="p1651507550165628"></a><a name="p1651507550165628"></a>Enumerates error codes of the permission management module. </p>
</td>
</tr>
</tbody>
</table>


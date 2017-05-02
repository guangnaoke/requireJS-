# requireJS-
requireJs 常用方法备忘

被引用文件一般方法设置

define('project',{
  return {
    data: {},
    function() {}
  }
});

引用文件一般方法设置

require(['project', jQ], (project, $)=> {
    test.name = project.name;
});
